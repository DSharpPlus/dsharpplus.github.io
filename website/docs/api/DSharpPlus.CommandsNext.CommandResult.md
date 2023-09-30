# Struct CommandResult

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a command's execution result.

```csharp
public struct CommandResult
```

## Properties

### <a id="DSharpPlus_CommandsNext_CommandResult_Context"></a>Context

Gets the context in which the command was executed.

```csharp
public readonly CommandContext Context { get; }
```

#### Property Value

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

### <a id="DSharpPlus_CommandsNext_CommandResult_Exception"></a>Exception

Gets the exception (if any) that occurred when executing the command.

```csharp
public readonly Exception Exception { get; }
```

#### Property Value

[Exception](https://learn.microsoft.com/dotnet/api/system.exception)

### <a id="DSharpPlus_CommandsNext_CommandResult_IsSuccessful"></a>IsSuccessful

Gets whether the command execution succeeded.

```csharp
public readonly bool IsSuccessful { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

