# Class DuplicateCommandException

Namespace: [DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)  
Assembly: DSharpPlus.CommandsNext.dll

Indicates that given command name or alias is taken.

```csharp
public class DuplicateCommandException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[DuplicateCommandException](DSharpPlus.CommandsNext.Exceptions.DuplicateCommandException.md)

## Properties

### <a id="DSharpPlus_CommandsNext_Exceptions_DuplicateCommandException_CommandName"></a>CommandName

Gets the name of the command that already exists.

```csharp
public string CommandName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_CommandsNext_Exceptions_DuplicateCommandException_ToString"></a>ToString\(\)

Returns a string representation of this <xref href="DSharpPlus.CommandsNext.Exceptions.DuplicateCommandException" data-throw-if-not-resolved="false"></xref>.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string representation.

