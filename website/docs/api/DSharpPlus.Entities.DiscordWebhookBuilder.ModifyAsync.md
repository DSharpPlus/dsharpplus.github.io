# Method ModifyAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordWebhookBuilder_ModifyAsync_DSharpPlus_Entities_DiscordWebhook_DSharpPlus_Entities_DiscordMessage_"></a>ModifyAsync\(DiscordWebhook, DiscordMessage\)

Sends the modified webhook message.

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordWebhook webhook, DiscordMessage message)
```

### Parameters

`webhook` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The webhook that should be executed.

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to modify.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The modified message

## <a id="DSharpPlus_Entities_DiscordWebhookBuilder_ModifyAsync_DSharpPlus_Entities_DiscordWebhook_System_UInt64_"></a>ModifyAsync\(DiscordWebhook, ulong\)

Sends the modified webhook message.

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordWebhook webhook, ulong messageId)
```

### Parameters

`webhook` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The webhook that should be executed.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the message to modify.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The modified message

