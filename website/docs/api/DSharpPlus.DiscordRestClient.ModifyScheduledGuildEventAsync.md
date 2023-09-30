# Method ModifyScheduledGuildEventAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyScheduledGuildEventAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_ScheduledGuildEventEditModel__"></a>ModifyScheduledGuildEventAsync\(ulong, ulong, Action<ScheduledGuildEventEditModel\>\)

Modify a scheduled guild event.

```csharp
public Task<DiscordScheduledGuildEvent> ModifyScheduledGuildEventAsync(ulong guildId, ulong eventId, Action<ScheduledGuildEventEditModel> mdl)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the event resides on.

`eventId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the event to modify.

`mdl` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ScheduledGuildEventEditModel](DSharpPlus.Net.Models.ScheduledGuildEventEditModel.md)\>

The action to apply to the event.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The modified event.

