# Method GetGuildBansAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildBansAsync_System_UInt64_System_Nullable_System_Int32__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetGuildBansAsync\(ulong, int?, ulong?, ulong?\)

Gets guild bans.

```csharp
public Task<IReadOnlyList<DiscordBan>> GetGuildBansAsync(ulong guild_id, int? limit = null, ulong? before = null, ulong? after = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to get the bans from.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The number of users to return (up to maximum 1000, default 1000).

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users before the given user ID.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users after the given user ID.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>\>

A collection of the guild's bans.

