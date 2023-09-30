# Class InteractionCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.InteractionCreated" data-throw-if-not-resolved="false"></xref>

```csharp
public class InteractionCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[InteractionCreateEventArgs](DSharpPlus.EventArgs.InteractionCreateEventArgs.md)

###### Derived

[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), 
[ContextMenuInteractionCreateEventArgs](DSharpPlus.EventArgs.ContextMenuInteractionCreateEventArgs.md), 
[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_InteractionCreateEventArgs_Interaction"></a>Interaction

Gets the interaction data that was invoked.

```csharp
public DiscordInteraction Interaction { get; }
```

#### Property Value

[DiscordInteraction](DSharpPlus.Entities.DiscordInteraction.md)

