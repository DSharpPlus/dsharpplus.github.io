# Method GetGuildWebhooksAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildWebhooksAsync_System_UInt64_"></a>GetGuildWebhooksAsync\(ulong\)

Gets all webhooks from a guild

```csharp
public Task<IReadOnlyList<DiscordWebhook>> GetGuildWebhooksAsync(ulong guild_id)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>\>

