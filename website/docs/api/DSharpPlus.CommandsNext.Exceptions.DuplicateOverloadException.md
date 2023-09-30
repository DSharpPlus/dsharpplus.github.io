# Class DuplicateOverloadException

Namespace: [DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)  
Assembly: DSharpPlus.CommandsNext.dll

Indicates that given argument set already exists as an overload for specified command.

```csharp
public class DuplicateOverloadException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[DuplicateOverloadException](DSharpPlus.CommandsNext.Exceptions.DuplicateOverloadException.md)

## Properties

### <a id="DSharpPlus_CommandsNext_Exceptions_DuplicateOverloadException_ArgumentTypes"></a>ArgumentTypes

Gets the ordered collection of argument types for the specified overload.

```csharp
public IReadOnlyList<Type> ArgumentTypes { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[Type](https://learn.microsoft.com/dotnet/api/system.type)\>

### <a id="DSharpPlus_CommandsNext_Exceptions_DuplicateOverloadException_CommandName"></a>CommandName

Gets the name of the command that already has the overload.

```csharp
public string CommandName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_CommandsNext_Exceptions_DuplicateOverloadException_ToString"></a>ToString\(\)

Returns a string representation of this <xref href="DSharpPlus.CommandsNext.Exceptions.DuplicateOverloadException" data-throw-if-not-resolved="false"></xref>.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string representation.

