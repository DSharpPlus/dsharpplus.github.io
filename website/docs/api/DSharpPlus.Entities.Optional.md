# Class Optional

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Helper methods for instantiating an <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref>.

```csharp
public static class Optional
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Optional](DSharpPlus.Entities.Optional.md)

## Remarks

This class only serves to allow type parameter inference on calls to <xref href="DSharpPlus.Entities.Optional.FromValue%60%601(%60%600)" data-throw-if-not-resolved="false"></xref> or
<xref href="DSharpPlus.Entities.Optional.FromNoValue%60%601" data-throw-if-not-resolved="false"></xref>.

## Methods

### <a id="DSharpPlus_Entities_Optional_FromNoValue__1"></a>FromNoValue<T\>\(\)

Creates a new empty <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> with no value and invalid state.

```csharp
public static Optional<T> FromNoValue<T>()
```

#### Returns

[Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

Created optional.

#### Type Parameters

`T` 

The type that the created instance is wrapping around.

### <a id="DSharpPlus_Entities_Optional_FromValue__1___0_"></a>FromValue<T\>\(T\)

Creates a new <xref href="DSharpPlus.Entities.Optional%601" data-throw-if-not-resolved="false"></xref> with specified value and valid state.

```csharp
public static Optional<T> FromValue<T>(T value)
```

#### Parameters

`value` T

Value to populate the optional with.

#### Returns

[Optional](DSharpPlus.Entities.Optional\-1.md)<T\>

Created optional.

#### Type Parameters

`T` 

Type of the value.

