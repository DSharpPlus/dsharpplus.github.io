# Method EditResponseAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_BaseContext_EditResponseAsync_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditResponseAsync\(DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits the interaction response.

```csharp
public Task<DiscordMessage> EditResponseAsync(DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The data to edit the response with.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

