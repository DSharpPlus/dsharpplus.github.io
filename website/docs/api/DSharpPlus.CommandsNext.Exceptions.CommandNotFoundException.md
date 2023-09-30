# Class CommandNotFoundException

Namespace: [DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)  
Assembly: DSharpPlus.CommandsNext.dll

Thrown when the command service fails to find a command.

```csharp
public sealed class CommandNotFoundException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[CommandNotFoundException](DSharpPlus.CommandsNext.Exceptions.CommandNotFoundException.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Exceptions_CommandNotFoundException__ctor_System_String_"></a>CommandNotFoundException\(string\)

Creates a new <xref href="DSharpPlus.CommandsNext.Exceptions.CommandNotFoundException" data-throw-if-not-resolved="false"></xref>.

```csharp
public CommandNotFoundException(string command)
```

#### Parameters

`command` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the command that was not found.

## Properties

### <a id="DSharpPlus_CommandsNext_Exceptions_CommandNotFoundException_CommandName"></a>CommandName

Gets the name of the command that was not found.

```csharp
public string CommandName { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_CommandsNext_Exceptions_CommandNotFoundException_ToString"></a>ToString\(\)

Returns a string representation of this <xref href="DSharpPlus.CommandsNext.Exceptions.CommandNotFoundException" data-throw-if-not-resolved="false"></xref>.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string representation.

