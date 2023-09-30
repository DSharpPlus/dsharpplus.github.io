# Method GetEventsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetEventsAsync_System_Boolean_"></a>GetEventsAsync\(bool\)

Gets the currently active or scheduled events in this guild.

```csharp
public Task<IReadOnlyList<DiscordScheduledGuildEvent>> GetEventsAsync(bool withUserCounts = false)
```

### Parameters

`withUserCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to include number of users subscribed to each event

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>\>

The active and scheduled events on the server, if any.

