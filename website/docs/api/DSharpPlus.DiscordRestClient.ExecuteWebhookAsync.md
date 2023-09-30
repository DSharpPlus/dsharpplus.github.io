# Method ExecuteWebhookAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ExecuteWebhookAsync_System_UInt64_System_String_DSharpPlus_Entities_DiscordWebhookBuilder_"></a>ExecuteWebhookAsync\(ulong, string, DiscordWebhookBuilder\)

Sends a message to a webhook

```csharp
public Task<DiscordMessage> ExecuteWebhookAsync(ulong webhook_id, string webhook_token, DiscordWebhookBuilder builder)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

Webhook builder filled with data to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

