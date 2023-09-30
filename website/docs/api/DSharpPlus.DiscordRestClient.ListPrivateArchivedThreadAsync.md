# Method ListPrivateArchivedThreadAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ListPrivateArchivedThreadAsync_System_UInt64_System_UInt64_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListPrivateArchivedThreadAsync\(ulong, ulong, DateTimeOffset?, int\)

Gets the threads that are public and archived for a channel.

```csharp
public Task<ThreadQueryResult> ListPrivateArchivedThreadAsync(ulong guildId, ulong channelId, DateTimeOffset? before = null, int limit = 0)
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

