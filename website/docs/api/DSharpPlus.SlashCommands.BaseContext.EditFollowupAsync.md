# Method EditFollowupAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_BaseContext_EditFollowupAsync_System_UInt64_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditFollowupAsync\(ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits a followup message.

```csharp
public Task<DiscordMessage> EditFollowupAsync(ulong followupMessageId, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

### Parameters

`followupMessageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the followup message to edit.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The webhook builder.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

