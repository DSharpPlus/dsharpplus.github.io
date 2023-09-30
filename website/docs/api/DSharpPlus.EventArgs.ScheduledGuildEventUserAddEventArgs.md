# Class ScheduledGuildEventUserAddEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Fired when someone subscribes to the scheduled event.

```csharp
public class ScheduledGuildEventUserAddEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ScheduledGuildEventUserAddEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md)

###### Derived

[ScheduledGuildEventUserRemoveEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserRemoveEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUserAddEventArgs_Event"></a>Event

The event that was subscribed to.

```csharp
public DiscordScheduledGuildEvent Event { get; }
```

#### Property Value

[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUserAddEventArgs_Guild"></a>Guild

The guild the event is scheduled for.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUserAddEventArgs_User"></a>User

The user that subscribed to the event.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

