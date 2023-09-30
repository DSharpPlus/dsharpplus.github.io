# Method EditWebhookMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_EditWebhookMessageAsync_System_UInt64_System_String_System_UInt64_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditWebhookMessageAsync\(ulong, string, ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits a previously-sent webhook message.

```csharp
public Task<DiscordMessage> EditWebhookMessageAsync(ulong webhook_id, string webhook_token, ulong messageId, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message to edit.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The builder of the message to edit.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The modified <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>

