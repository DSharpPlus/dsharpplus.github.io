# Class ScheduledGuildEventUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Fired when an event is updated.

```csharp
public class ScheduledGuildEventUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[ScheduledGuildEventUpdateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUpdateEventArgs_EventAfter"></a>EventAfter

The event after the update.

```csharp
public DiscordScheduledGuildEvent EventAfter { get; }
```

#### Property Value

[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

### <a id="DSharpPlus_EventArgs_ScheduledGuildEventUpdateEventArgs_EventBefore"></a>EventBefore

The event before the update, or null if it wasn't cached.

```csharp
public DiscordScheduledGuildEvent EventBefore { get; }
```

#### Property Value

[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

