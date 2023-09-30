# Method GetCurrentUserGuildsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetCurrentUserGuildsAsync_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetCurrentUserGuildsAsync\(int, ulong?, ulong?\)

Gets current user's guilds

```csharp
public Task<IReadOnlyList<DiscordGuild>> GetCurrentUserGuildsAsync(int limit = 100, ulong? before = null, ulong? after = null)
```

### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit of guilds to get

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets guild before ID

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets guilds after ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>\>

