# Method GetScheduledGuildEventUsersAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetScheduledGuildEventUsersAsync_System_UInt64_System_UInt64_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetScheduledGuildEventUsersAsync\(ulong, ulong, int, ulong?, ulong?\)

Gets the users interested in the guild event.

```csharp
public Task<IReadOnlyList<DiscordUser>> GetScheduledGuildEventUsersAsync(ulong guildId, ulong eventId, int limit = 100, ulong? after = null, ulong? before = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the event resides on.

`eventId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the event.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How many users to query.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users after this ID.

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users before this ID.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

The users interested in the event.

