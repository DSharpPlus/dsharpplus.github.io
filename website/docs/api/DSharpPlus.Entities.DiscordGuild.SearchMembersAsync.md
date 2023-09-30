# Method SearchMembersAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_SearchMembersAsync_System_String_System_Nullable_System_Int32__"></a>SearchMembersAsync\(string, int?\)

Searches the current guild for members who's display name start with the specified name.

```csharp
public Task<IReadOnlyList<DiscordMember>> SearchMembersAsync(string name, int? limit = 1)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name to search for.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The maximum amount of members to return. Max 1000. Defaults to 1.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

The members found, if any.

