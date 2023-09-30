# Method DeleteWebhookMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteWebhookMessageAsync_System_UInt64_System_String_System_UInt64_"></a>DeleteWebhookMessageAsync\(ulong, string, ulong\)

Deletes a message that was created by a webhook.

```csharp
public Task DeleteWebhookMessageAsync(ulong webhook_id, string webhook_token, ulong messageId)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message to delete

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

