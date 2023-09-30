# Method GetEventUsersAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetEventUsersAsync_DSharpPlus_Entities_DiscordScheduledGuildEvent_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetEventUsersAsync\(DiscordScheduledGuildEvent, int, ulong?, ulong?\)

Gets a list of users who are interested in this event.

```csharp
public Task<IReadOnlyList<DiscordUser>> GetEventUsersAsync(DiscordScheduledGuildEvent guildEvent, int limit = 100, ulong? after = null, ulong? before = null)
```

### Parameters

`guildEvent` [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

The event to query users from

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How many users to fetch.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users after this id. Mutually exclusive with before

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users before this id. Mutually exclusive with after

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

