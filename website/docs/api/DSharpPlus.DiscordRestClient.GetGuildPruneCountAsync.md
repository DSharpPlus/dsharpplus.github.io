# Method GetGuildPruneCountAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildPruneCountAsync_System_UInt64_System_Int32_System_Collections_Generic_IEnumerable_System_UInt64__"></a>GetGuildPruneCountAsync\(ulong, int, IEnumerable<ulong\>\)

Get a guild's prune count.

```csharp
public Task<int> GetGuildPruneCountAsync(ulong guild_id, int days, IEnumerable<ulong> include_roles)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Days to check for

`include\_roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

The roles to be included in the prune.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

