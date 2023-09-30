# Class ScheduledGuildEventCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Fired when a new scheduled guild event is created.

```csharp
public class ScheduledGuildEventCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ScheduledGuildEventCreateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventCreateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventCreateEventArgs_Channel"></a>Channel

The channel this event is scheduled for, if applicable.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventCreateEventArgs_Creator"></a>Creator

The user that created the event.

```csharp
public DiscordUser Creator { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventCreateEventArgs_Event"></a>Event

The event that was created.

```csharp
public DiscordScheduledGuildEvent Event { get; }
```

#### Property Value

[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventCreateEventArgs_Guild"></a>Guild

The guild this event is scheduled for.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

