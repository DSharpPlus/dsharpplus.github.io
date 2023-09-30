# Class ScheduledGuildEventUserRemoveEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Fired when someone unsubcribes from an event.

```csharp
public class ScheduledGuildEventUserRemoveEventArgs : ScheduledGuildEventUserAddEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ScheduledGuildEventUserAddEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md) ← 
[ScheduledGuildEventUserRemoveEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserRemoveEventArgs.md)

###### Inherited Members

[ScheduledGuildEventUserAddEventArgs.Guild](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md\#DSharpPlus\_EventArgs\_ScheduledGuildEventUserAddEventArgs\_Guild), 
[ScheduledGuildEventUserAddEventArgs.Event](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md\#DSharpPlus\_EventArgs\_ScheduledGuildEventUserAddEventArgs\_Event), 
[ScheduledGuildEventUserAddEventArgs.User](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md\#DSharpPlus\_EventArgs\_ScheduledGuildEventUserAddEventArgs\_User), 
[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUserRemoveEventArgs_Event"></a>Event

The event that was unsubscribed from.

```csharp
public DiscordScheduledGuildEvent Event { get; }
```

#### Property Value

[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUserRemoveEventArgs_Guild"></a>Guild

The guild the event is scheduled for.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUserRemoveEventArgs_User"></a>User

The user that unsubscribed from the event.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

