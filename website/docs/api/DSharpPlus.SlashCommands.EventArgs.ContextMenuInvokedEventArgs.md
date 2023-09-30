# Class ContextMenuInvokedEventArgs

Namespace: [DSharpPlus.SlashCommands.EventArgs](DSharpPlus.SlashCommands.EventArgs.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents arguments for a <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension.ContextMenuInvoked" data-throw-if-not-resolved="false"></xref>

```csharp
public sealed class ContextMenuInvokedEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[ContextMenuInvokedEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuInvokedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_SlashCommands_EventArgs_ContextMenuInvokedEventArgs_Context"></a>Context

The context of the command.

```csharp
public ContextMenuContext Context { get; }
```

#### Property Value

[ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md)

