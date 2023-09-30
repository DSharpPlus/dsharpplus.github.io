# Method DeleteWebhookAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteWebhookAsync_System_UInt64_System_String_"></a>DeleteWebhookAsync\(ulong, string\)

Deletes a webhook

```csharp
public Task DeleteWebhookAsync(ulong webhook_id, string reason)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this webhook was deleted

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_DiscordRestClient_DeleteWebhookAsync_System_UInt64_System_String_System_String_"></a>DeleteWebhookAsync\(ulong, string, string\)

Deletes a webhook (when user is not in said guild)

```csharp
public Task DeleteWebhookAsync(ulong webhook_id, string reason, string webhook_token)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this webhook was removed

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

