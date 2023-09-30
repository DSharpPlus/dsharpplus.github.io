# Method EditOriginalInteractionResponseAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_EditOriginalInteractionResponseAsync_System_String_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditOriginalInteractionResponseAsync\(string, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits the original interaction response.

```csharp
public Task<DiscordMessage> EditOriginalInteractionResponseAsync(string interactionToken, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The webhook builder.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> edited.

