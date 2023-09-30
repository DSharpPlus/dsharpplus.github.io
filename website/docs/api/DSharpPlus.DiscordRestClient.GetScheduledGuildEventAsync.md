# Method GetScheduledGuildEventAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetScheduledGuildEventAsync_System_UInt64_System_UInt64_"></a>GetScheduledGuildEventAsync\(ulong, ulong\)

Gets a specific scheduled guild event.

```csharp
public Task<DiscordScheduledGuildEvent> GetScheduledGuildEventAsync(ulong guildId, ulong eventId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the event resides on.

`eventId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the event to get

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The requested event.

