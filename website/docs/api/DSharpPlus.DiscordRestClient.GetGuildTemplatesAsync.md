# Method GetGuildTemplatesAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildTemplatesAsync_System_UInt64_"></a>GetGuildTemplatesAsync\(ulong\)

Gets a guild's templates.

```csharp
public Task<IReadOnlyList<DiscordGuildTemplate>> GetGuildTemplatesAsync(ulong guild_id)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>\>

All of the guild's templates.

