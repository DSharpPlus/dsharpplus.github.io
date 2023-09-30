# Method BroadcastMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordWebhookClient_BroadcastMessageAsync_DSharpPlus_Entities_DiscordWebhookBuilder_"></a>BroadcastMessageAsync\(DiscordWebhookBuilder\)

Broadcasts a message to all registered webhooks.

```csharp
public Task<Dictionary<DiscordWebhook, DiscordMessage>> BroadcastMessageAsync(DiscordWebhookBuilder builder)
```

### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

Webhook builder filled with data to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[Dictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.dictionary\-2)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md), [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

