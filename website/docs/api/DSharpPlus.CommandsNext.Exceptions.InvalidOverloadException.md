# Class InvalidOverloadException

Namespace: [DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)  
Assembly: DSharpPlus.CommandsNext.dll

Thrown when the command service fails to build a command due to a problem with its overload.

```csharp
public sealed class InvalidOverloadException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[InvalidOverloadException](DSharpPlus.CommandsNext.Exceptions.InvalidOverloadException.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Exceptions_InvalidOverloadException__ctor_System_String_System_Reflection_MethodInfo_System_Reflection_ParameterInfo_"></a>InvalidOverloadException\(string, MethodInfo, ParameterInfo?\)

Creates a new <xref href="DSharpPlus.CommandsNext.Exceptions.InvalidOverloadException" data-throw-if-not-resolved="false"></xref>.

```csharp
public InvalidOverloadException(string message, MethodInfo method, ParameterInfo? parameter)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

Exception message.

`method` [MethodInfo](https://learn.microsoft.com/dotnet/api/system.reflection.methodinfo)

Method that caused the problem.

`parameter` [ParameterInfo](https://learn.microsoft.com/dotnet/api/system.reflection.parameterinfo)?

Method argument that caused the problem.

### <a id="DSharpPlus_CommandsNext_Exceptions_InvalidOverloadException__ctor_System_String_System_Reflection_MethodInfo_"></a>InvalidOverloadException\(string, MethodInfo\)

Creates a new <xref href="DSharpPlus.CommandsNext.Exceptions.InvalidOverloadException" data-throw-if-not-resolved="false"></xref>.

```csharp
public InvalidOverloadException(string message, MethodInfo method)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

Exception message.

`method` [MethodInfo](https://learn.microsoft.com/dotnet/api/system.reflection.methodinfo)

Method that caused the problem.

## Properties

### <a id="DSharpPlus_CommandsNext_Exceptions_InvalidOverloadException_Method"></a>Method

Gets the method that caused this exception.

```csharp
public MethodInfo Method { get; }
```

#### Property Value

[MethodInfo](https://learn.microsoft.com/dotnet/api/system.reflection.methodinfo)

### <a id="DSharpPlus_CommandsNext_Exceptions_InvalidOverloadException_Parameter"></a>Parameter

Gets or sets the argument that caused the problem. This can be null.

```csharp
public ParameterInfo? Parameter { get; }
```

#### Property Value

[ParameterInfo](https://learn.microsoft.com/dotnet/api/system.reflection.parameterinfo)?

## Methods

### <a id="DSharpPlus_CommandsNext_Exceptions_InvalidOverloadException_ToString"></a>ToString\(\)

Returns a string representation of this <xref href="DSharpPlus.CommandsNext.Exceptions.InvalidOverloadException" data-throw-if-not-resolved="false"></xref>.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string representation.

