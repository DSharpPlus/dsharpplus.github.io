# Method GetWebhookWithTokenAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetWebhookWithTokenAsync_System_UInt64_System_String_"></a>GetWebhookWithTokenAsync\(ulong, string\)

Gets a webhook with its token (when user is not in said guild)

```csharp
public Task<DiscordWebhook> GetWebhookWithTokenAsync(ulong webhook_id, string webhook_token)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

