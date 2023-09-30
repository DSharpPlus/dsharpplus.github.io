# Method SearchMembersAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_SearchMembersAsync_System_UInt64_System_String_System_Nullable_System_Int32__"></a>SearchMembersAsync\(ulong, string, int?\)

Searches the given guild for members who's display name start with the specified name.

```csharp
public Task<IReadOnlyList<DiscordMember>> SearchMembersAsync(ulong guild_id, string name, int? limit = 1)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to search.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name to search for.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The maximum amount of members to return. Max 1000. Defaults to 1.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

The members found, if any.

