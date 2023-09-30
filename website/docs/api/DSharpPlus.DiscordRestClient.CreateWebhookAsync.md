# Method CreateWebhookAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateWebhookAsync_System_UInt64_System_String_System_String_System_String_"></a>CreateWebhookAsync\(ulong, string, string, string\)

Creates a new webhook

```csharp
public Task<DiscordWebhook> CreateWebhookAsync(ulong channel_id, string name, string base64_avatar, string reason)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook name

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook avatar (base64)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was created

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

## <a id="DSharpPlus_DiscordRestClient_CreateWebhookAsync_System_UInt64_System_String_System_IO_Stream_System_String_"></a>CreateWebhookAsync\(ulong, string, Stream, string\)

Creates a new webhook

```csharp
public Task<DiscordWebhook> CreateWebhookAsync(ulong channel_id, string name, Stream avatar = null, string reason = null)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook name

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Webhook avatar

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was created

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

