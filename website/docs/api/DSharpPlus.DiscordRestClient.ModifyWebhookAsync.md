# Method ModifyWebhookAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_UInt64_System_String_System_String_System_String_"></a>ModifyWebhookAsync\(ulong, ulong, string, string, string\)

Modifies a webhook

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, ulong channelId, string name, string base64_avatar, string reason)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The new channel ID the webhook should be moved to.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook avatar (base64)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

## <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_UInt64_System_String_System_IO_Stream_System_String_"></a>ModifyWebhookAsync\(ulong, ulong, string, Stream, string\)

Modifies a webhook

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, ulong channelId, string name, Stream avatar, string reason)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The new channel ID the webhook should be moved to.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

New webhook avatar

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

## <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_String_System_String_System_String_System_String_"></a>ModifyWebhookAsync\(ulong, string, string, string, string\)

Modifies a webhook (when user is not in said guild)

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, string name, string base64_avatar, string webhook_token, string reason)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook avatar (base64)

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

## <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_String_System_IO_Stream_System_String_System_String_"></a>ModifyWebhookAsync\(ulong, string, Stream, string, string\)

Modifies a webhook (when user is not in said guild)

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, string name, Stream avatar, string webhook_token, string reason)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

New webhook avatar

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

