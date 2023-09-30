# Class ChecksFailedException

Namespace: [DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)  
Assembly: DSharpPlus.CommandsNext.dll

Indicates that one or more checks for given command have failed.

```csharp
public class ChecksFailedException : Exception
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[ChecksFailedException](DSharpPlus.CommandsNext.Exceptions.ChecksFailedException.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Exceptions_ChecksFailedException__ctor_DSharpPlus_CommandsNext_Command_DSharpPlus_CommandsNext_CommandContext_System_Collections_Generic_IEnumerable_DSharpPlus_CommandsNext_Attributes_CheckBaseAttribute__"></a>ChecksFailedException\(Command, CommandContext, IEnumerable<CheckBaseAttribute\>\)

Creates a new <xref href="DSharpPlus.CommandsNext.Exceptions.ChecksFailedException" data-throw-if-not-resolved="false"></xref>.

```csharp
public ChecksFailedException(Command command, CommandContext ctx, IEnumerable<CheckBaseAttribute> failedChecks)
```

#### Parameters

`command` [Command](DSharpPlus.CommandsNext.Command.md)

Command that failed to execute.

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the command was executed.

`failedChecks` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>

A collection of checks that failed.

## Properties

### <a id="DSharpPlus_CommandsNext_Exceptions_ChecksFailedException_Command"></a>Command

Gets the command that was executed.

```csharp
public Command Command { get; }
```

#### Property Value

[Command](DSharpPlus.CommandsNext.Command.md)

### <a id="DSharpPlus_CommandsNext_Exceptions_ChecksFailedException_Context"></a>Context

Gets the context in which given command was executed.

```csharp
public CommandContext Context { get; }
```

#### Property Value

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

### <a id="DSharpPlus_CommandsNext_Exceptions_ChecksFailedException_FailedChecks"></a>FailedChecks

Gets the checks that failed.

```csharp
public IReadOnlyList<CheckBaseAttribute> FailedChecks { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>

