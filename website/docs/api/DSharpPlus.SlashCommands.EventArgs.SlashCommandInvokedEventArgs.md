# Class SlashCommandInvokedEventArgs

Namespace: [DSharpPlus.SlashCommands.EventArgs](DSharpPlus.SlashCommands.EventArgs.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents the arguments for a <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension.SlashCommandInvoked" data-throw-if-not-resolved="false"></xref> event.

```csharp
public sealed class SlashCommandInvokedEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[SlashCommandInvokedEventArgs](DSharpPlus.SlashCommands.EventArgs.SlashCommandInvokedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_SlashCommands_EventArgs_SlashCommandInvokedEventArgs_Context"></a>Context

The context of the command.

```csharp
public InteractionContext Context { get; }
```

#### Property Value

[InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

