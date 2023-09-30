# Method AddWebhookAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordWebhookClient_AddWebhookAsync_System_UInt64_System_String_"></a>AddWebhookAsync\(ulong, string\)

Registers a webhook with this client. This retrieves a webhook based on the ID and token supplied.

```csharp
public Task<DiscordWebhook> AddWebhookAsync(ulong id, string token)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the webhook to add.

`token` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the webhook to add.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

The registered webhook.

## <a id="DSharpPlus_DiscordWebhookClient_AddWebhookAsync_System_Uri_"></a>AddWebhookAsync\(Uri\)

Registers a webhook with this client. This retrieves a webhook from webhook URL.

```csharp
public Task<DiscordWebhook> AddWebhookAsync(Uri url)
```

### Parameters

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

URL of the webhook to retrieve. This URL must contain both ID and token.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

The registered webhook.

## <a id="DSharpPlus_DiscordWebhookClient_AddWebhookAsync_System_UInt64_DSharpPlus_BaseDiscordClient_"></a>AddWebhookAsync\(ulong, BaseDiscordClient\)

Registers a webhook with this client. This retrieves a webhook using the supplied full discord client.

```csharp
public Task<DiscordWebhook> AddWebhookAsync(ulong id, BaseDiscordClient client)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the webhook to register.

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

Discord client to which the webhook will belong.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

The registered webhook.

