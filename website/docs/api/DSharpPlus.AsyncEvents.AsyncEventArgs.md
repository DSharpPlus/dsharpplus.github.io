# Class AsyncEventArgs

Namespace: [DSharpPlus.AsyncEvents](DSharpPlus.AsyncEvents.md)  
Assembly: DSharpPlus.dll

A base class for arguments passed to an event handler.

```csharp
public class AsyncEventArgs : EventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md)

###### Derived

[AutocompleteErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.AutocompleteErrorEventArgs.md), 
[AutocompleteExecutedEventArgs](DSharpPlus.SlashCommands.EventArgs.AutocompleteExecutedEventArgs.md), 
[CommandEventArgs](DSharpPlus.CommandsNext.CommandEventArgs.md), 
[ContextMenuErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuErrorEventArgs.md), 
[ContextMenuExecutedEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuExecutedEventArgs.md), 
[ContextMenuInvokedEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuInvokedEventArgs.md), 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md), 
[GuildConnectionCreatedEventArgs](DSharpPlus.Lavalink.EventArgs.GuildConnectionCreatedEventArgs.md), 
[GuildConnectionRemovedEventArgs](DSharpPlus.Lavalink.EventArgs.GuildConnectionRemovedEventArgs.md), 
[NodeDisconnectedEventArgs](DSharpPlus.Lavalink.EventArgs.NodeDisconnectedEventArgs.md), 
[PlayerUpdateEventArgs](DSharpPlus.Lavalink.EventArgs.PlayerUpdateEventArgs.md), 
[SlashCommandErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.SlashCommandErrorEventArgs.md), 
[SlashCommandExecutedEventArgs](DSharpPlus.SlashCommands.EventArgs.SlashCommandExecutedEventArgs.md), 
[SlashCommandInvokedEventArgs](DSharpPlus.SlashCommands.EventArgs.SlashCommandInvokedEventArgs.md), 
[SocketMessageEventArgs](DSharpPlus.EventArgs.SocketMessageEventArgs.md), 
[StatisticsReceivedEventArgs](DSharpPlus.Lavalink.EventArgs.StatisticsReceivedEventArgs.md), 
[TrackExceptionEventArgs](DSharpPlus.Lavalink.EventArgs.TrackExceptionEventArgs.md), 
[TrackFinishEventArgs](DSharpPlus.Lavalink.EventArgs.TrackFinishEventArgs.md), 
[TrackStartEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStartEventArgs.md), 
[TrackStuckEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStuckEventArgs.md), 
[WebSocketCloseEventArgs](DSharpPlus.Lavalink.EventArgs.WebSocketCloseEventArgs.md)

## Properties

### <a id="DSharpPlus_AsyncEvents_AsyncEventArgs_Handled"></a>Handled

[UNUSED] This used to set whether an event was handled.

```csharp
[Obsolete("This is no longer utilized in DSharpPlus.", true)]
public bool Handled { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

