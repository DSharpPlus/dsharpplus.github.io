# Method ListGuildMembersAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ListGuildMembersAsync_System_UInt64_System_Nullable_System_Int32__System_Nullable_System_UInt64__"></a>ListGuildMembersAsync\(ulong, int?, ulong?\)

Gets all guild members

```csharp
public Task<IReadOnlyList<DiscordMember>> ListGuildMembersAsync(ulong guild_id, int? limit, ulong? after)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Member download limit

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets members after this ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

