# Class CommandEventArgs

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Base class for all CNext-related events.

```csharp
public class CommandEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[CommandEventArgs](DSharpPlus.CommandsNext.CommandEventArgs.md)

###### Derived

[CommandErrorEventArgs](DSharpPlus.CommandsNext.CommandErrorEventArgs.md), 
[CommandExecutionEventArgs](DSharpPlus.CommandsNext.CommandExecutionEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandEventArgs_Command"></a>Command

Gets the command that was executed.

```csharp
public Command? Command { get; }
```

#### Property Value

[Command](DSharpPlus.CommandsNext.Command.md)?

### <a id="DSharpPlus_CommandsNext_CommandEventArgs_Context"></a>Context

Gets the context in which the command was executed.

```csharp
public CommandContext Context { get; }
```

#### Property Value

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

