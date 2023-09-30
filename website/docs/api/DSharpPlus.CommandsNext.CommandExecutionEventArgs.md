# Class CommandExecutionEventArgs

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents arguments for <xref href="DSharpPlus.CommandsNext.CommandsNextExtension.CommandExecuted" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class CommandExecutionEventArgs : CommandEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[CommandEventArgs](DSharpPlus.CommandsNext.CommandEventArgs.md) ← 
[CommandExecutionEventArgs](DSharpPlus.CommandsNext.CommandExecutionEventArgs.md)

###### Inherited Members

[CommandEventArgs.Context](DSharpPlus.CommandsNext.CommandEventArgs.md\#DSharpPlus\_CommandsNext\_CommandEventArgs\_Context), 
[CommandEventArgs.Command](DSharpPlus.CommandsNext.CommandEventArgs.md\#DSharpPlus\_CommandsNext\_CommandEventArgs\_Command), 
[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandExecutionEventArgs_Command"></a>Command

Gets the command that was executed.

```csharp
public Command Command { get; }
```

#### Property Value

[Command](DSharpPlus.CommandsNext.Command.md)

