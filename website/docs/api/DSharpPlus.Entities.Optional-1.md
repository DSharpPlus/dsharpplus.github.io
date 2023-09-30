# Struct Optional<T\>

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a wrapper which may or may not have a value.

```csharp
[JsonConverter(typeof(OptionalJsonConverter))]
public readonly struct Optional<T> : IOptional
```

#### Type Parameters

`T` 

Type of the value.

###### Implements

[IOptional](DSharpPlus.Entities.IOptional.md)

## Constructors

### <a id="DSharpPlus_Entities_Optional_1__ctor__0_"></a>Optional\(T\)

Creates a new <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> with specified value.

```csharp
public Optional(T value)
```

#### Parameters

`value` T

Value of this option.

## Properties

### <a id="DSharpPlus_Entities_Optional_1_HasValue"></a>HasValue

Gets whether this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> has a value.

```csharp
public bool HasValue { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_Optional_1_Value"></a>Value

Gets the value of this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>.

```csharp
public T Value { get; }
```

#### Property Value

T

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

If this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> has no value.

## Methods

### <a id="DSharpPlus_Entities_Optional_1_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> (or its value) are equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> or its value.

### <a id="DSharpPlus_Entities_Optional_1_Equals_DSharpPlus_Entities_Optional__0__"></a>Equals\(Optional<T\>\)

Checks whether this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(Optional<T> e)
```

#### Parameters

`e` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

<xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_Optional_1_Equals__0_"></a>Equals\(T\)

Checks whether the value of this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> is equal to specified object.

```csharp
public bool Equals(T e)
```

#### Parameters

`e` T

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to the value of this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_Optional_1_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_Optional_1_IfPresent__1_System_Func__0___0__"></a>IfPresent<TTarget\>\(Func<T, TTarget\>\)

Performs a mapping operation on the current <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>, turning it into an Optional holding a
<code class="typeparamref">TTarget</code> instance if the source optional contains a value; otherwise, returns an
<xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> of that same type with no value.

```csharp
public Optional<TTarget> IfPresent<TTarget>(Func<T, TTarget> mapper)
```

#### Parameters

`mapper` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<T, TTarget\>

The mapping function to apply on the current value if it exists

#### Returns

[Optional](DSharpPlus.Entities.Optional\-1.md)<TTarget\>

An <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> containing a value denoted by calling <code class="paramref">mapper</code> if the current
<xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> contains a value; otherwise, an empty <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> of the target
type.

#### Type Parameters

`TTarget` 

The type of the target value returned by <code class="paramref">mapper</code>

### <a id="DSharpPlus_Entities_Optional_1_IsDefined__0__"></a>IsDefined\(out T?\)

Determines whether the optional has a value, and the value is non-null.

```csharp
public bool IsDefined(out T? value)
```

#### Parameters

`value` T?

The value contained within the optional.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

True if the value is set, and is not null, otherwise false.

### <a id="DSharpPlus_Entities_Optional_1_ToString"></a>ToString\(\)

Returns a string representation of this optional value.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this optional value.

## Operators

### <a id="DSharpPlus_Entities_Optional_1_op_Equality_DSharpPlus_Entities_Optional__0__DSharpPlus_Entities_Optional__0__"></a>operator ==\(Optional<T\>, Optional<T\>\)

```csharp
public static bool operator ==(Optional<T> opt1, Optional<T> opt2)
```

#### Parameters

`opt1` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

`opt2` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_Optional_1_op_Equality_DSharpPlus_Entities_Optional__0___0_"></a>operator ==\(Optional<T\>, T\)

```csharp
public static bool operator ==(Optional<T> opt, T t)
```

#### Parameters

`opt` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

`t` T

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_Optional_1_op_Explicit_DSharpPlus_Entities_Optional__0____0"></a>explicit operator T\(Optional<T\>\)

```csharp
public static explicit operator T(Optional<T> opt)
```

#### Parameters

`opt` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

#### Returns

T

### <a id="DSharpPlus_Entities_Optional_1_op_Implicit__0__DSharpPlus_Entities_Optional__0_"></a>implicit operator Optional<T\>\(T\)

```csharp
public static implicit operator Optional<T>(T val)
```

#### Parameters

`val` T

#### Returns

[Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

### <a id="DSharpPlus_Entities_Optional_1_op_Inequality_DSharpPlus_Entities_Optional__0__DSharpPlus_Entities_Optional__0__"></a>operator \!=\(Optional<T\>, Optional<T\>\)

```csharp
public static bool operator !=(Optional<T> opt1, Optional<T> opt2)
```

#### Parameters

`opt1` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

`opt2` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_Optional_1_op_Inequality_DSharpPlus_Entities_Optional__0___0_"></a>operator \!=\(Optional<T\>, T\)

```csharp
public static bool operator !=(Optional<T> opt, T t)
```

#### Parameters

`opt` [Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

`t` T

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

