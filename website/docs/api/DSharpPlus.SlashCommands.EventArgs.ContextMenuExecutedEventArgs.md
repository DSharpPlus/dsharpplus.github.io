# Class ContextMenuExecutedEventArgs

Namespace: [DSharpPlus.SlashCommands.EventArgs](DSharpPlus.SlashCommands.EventArgs.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents arguments for a <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension.ContextMenuExecuted" data-throw-if-not-resolved="false"></xref>

```csharp
public sealed class ContextMenuExecutedEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[ContextMenuExecutedEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuExecutedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_SlashCommands_EventArgs_ContextMenuExecutedEventArgs_Context"></a>Context

The context of the command.

```csharp
public ContextMenuContext Context { get; }
```

#### Property Value

[ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md)

