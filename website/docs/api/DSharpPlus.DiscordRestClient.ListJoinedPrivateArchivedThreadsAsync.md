# Method ListJoinedPrivateArchivedThreadsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ListJoinedPrivateArchivedThreadsAsync_System_UInt64_System_UInt64_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListJoinedPrivateArchivedThreadsAsync\(ulong, ulong, DateTimeOffset?, int\)

Gets the private archived threads the user has joined for a channel.

```csharp
public Task<ThreadQueryResult> ListJoinedPrivateArchivedThreadsAsync(ulong guildId, ulong channelId, DateTimeOffset? before = null, int limit = 0)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Date to filter by.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

