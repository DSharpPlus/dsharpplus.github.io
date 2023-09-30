# Method BeginGuildPruneAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_BeginGuildPruneAsync_System_UInt64_System_Int32_System_Boolean_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>BeginGuildPruneAsync\(ulong, int, bool, IEnumerable<ulong\>, string\)

Begins a guild prune.

```csharp
public Task<int?> BeginGuildPruneAsync(ulong guild_id, int days, bool compute_prune_count, IEnumerable<ulong> include_roles, string reason)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Days to prune for

`compute\_prune\_count` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to return the prune count after this method completes. This is discouraged for larger guilds.

`include\_roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

The roles to be included in the prune.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this guild was pruned

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

