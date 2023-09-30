# Class DiscordMessage

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord text message.

```csharp
public class DiscordMessage : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

###### Extension Methods

[MessageExtensions.CollectReactionsAsync\(DiscordMessage, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_CollectReactionsAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.DoPollAsync\(DiscordMessage, IEnumerable<DiscordEmoji\>, PollBehaviour?, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_DoPollAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordEmoji\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PollBehaviour\_\_System\_Nullable\_System\_TimeSpan\_\_), 
[CommandsNextUtilities.GetMentionPrefixLength\(DiscordMessage, DiscordUser\)](DSharpPlus.CommandsNext.CommandsNextUtilities.md\#DSharpPlus\_CommandsNext\_CommandsNextUtilities\_GetMentionPrefixLength\_DSharpPlus\_Entities\_DiscordMessage\_DSharpPlus\_Entities\_DiscordUser\_), 
[MessageExtensions.GetNextMessageAsync\(DiscordMessage, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_GetNextMessageAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.GetNextMessageAsync\(DiscordMessage, Func<DiscordMessage, bool\>, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_GetNextMessageAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Func\_DSharpPlus\_Entities\_DiscordMessage\_System\_Boolean\_\_System\_Nullable\_System\_TimeSpan\_\_), 
[CommandsNextUtilities.GetStringPrefixLength\(DiscordMessage, string, StringComparison\)](DSharpPlus.CommandsNext.CommandsNextUtilities.md\#DSharpPlus\_CommandsNext\_CommandsNextUtilities\_GetStringPrefixLength\_DSharpPlus\_Entities\_DiscordMessage\_System\_String\_System\_StringComparison\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, CancellationToken\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Threading\_CancellationToken\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, string, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_String\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, string, CancellationToken\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_String\_System\_Threading\_CancellationToken\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, DiscordUser, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_DSharpPlus\_Entities\_DiscordUser\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, DiscordUser, CancellationToken\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_DSharpPlus\_Entities\_DiscordUser\_System\_Threading\_CancellationToken\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Func\_DSharpPlus\_EventArgs\_ComponentInteractionCreateEventArgs\_System\_Boolean\_\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForButtonAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Func\_DSharpPlus\_EventArgs\_ComponentInteractionCreateEventArgs\_System\_Boolean\_\_System\_Threading\_CancellationToken\_), 
[MessageExtensions.WaitForReactionAsync\(DiscordMessage, DiscordUser, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForReactionAsync\_DSharpPlus\_Entities\_DiscordMessage\_DSharpPlus\_Entities\_DiscordUser\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForReactionAsync\(DiscordMessage, DiscordUser, DiscordEmoji, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForReactionAsync\_DSharpPlus\_Entities\_DiscordMessage\_DSharpPlus\_Entities\_DiscordUser\_DSharpPlus\_Entities\_DiscordEmoji\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForSelectAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Func\_DSharpPlus\_EventArgs\_ComponentInteractionCreateEventArgs\_System\_Boolean\_\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForSelectAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_Func\_DSharpPlus\_EventArgs\_ComponentInteractionCreateEventArgs\_System\_Boolean\_\_System\_Threading\_CancellationToken\_), 
[MessageExtensions.WaitForSelectAsync\(DiscordMessage, string, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForSelectAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_String\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForSelectAsync\(DiscordMessage, string, CancellationToken\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForSelectAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_String\_System\_Threading\_CancellationToken\_), 
[MessageExtensions.WaitForSelectAsync\(DiscordMessage, DiscordUser, string, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForSelectAsync\_DSharpPlus\_Entities\_DiscordMessage\_DSharpPlus\_Entities\_DiscordUser\_System\_String\_System\_Nullable\_System\_TimeSpan\_\_), 
[MessageExtensions.WaitForSelectAsync\(DiscordMessage, DiscordUser, string, CancellationToken\)](DSharpPlus.Interactivity.Extensions.MessageExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_MessageExtensions\_WaitForSelectAsync\_DSharpPlus\_Entities\_DiscordMessage\_DSharpPlus\_Entities\_DiscordUser\_System\_String\_System\_Threading\_CancellationToken\_)

## Properties

### <a id="DSharpPlus_Entities_DiscordMessage_Activity"></a>Activity

Gets the message activity in the Rich Presence embed.

```csharp
[JsonProperty("activity", NullValueHandling = NullValueHandling.Ignore)]
public DiscordMessageActivity Activity { get; }
```

#### Property Value

[DiscordMessageActivity](DSharpPlus.Entities.DiscordMessageActivity.md)

### <a id="DSharpPlus_Entities_DiscordMessage_Application"></a>Application

Gets the message application in the Rich Presence embed.

```csharp
[JsonProperty("application", NullValueHandling = NullValueHandling.Ignore)]
public DiscordMessageApplication Application { get; }
```

#### Property Value

[DiscordMessageApplication](DSharpPlus.Entities.DiscordMessageApplication.md)

### <a id="DSharpPlus_Entities_DiscordMessage_ApplicationId"></a>ApplicationId

Gets the id of the interaction application, if a response to an interaction.

```csharp
[JsonProperty("application_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? ApplicationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordMessage_Attachments"></a>Attachments

Gets files attached to this message.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordAttachment> Attachments { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_Author"></a>Author

Gets the user or member that sent the message.

```csharp
[JsonProperty("author", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUser Author { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_Entities_DiscordMessage_Channel"></a>Channel

Gets the channel in which the message was sent.

```csharp
[JsonIgnore]
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordMessage_ChannelId"></a>ChannelId

Gets the ID of the channel in which the message was sent.

```csharp
[JsonProperty("channel_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordMessage_Components"></a>Components

Gets the components this message was sent with.

```csharp
[JsonProperty("components", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyCollection<DiscordActionRowComponent> Components { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_Content"></a>Content

Gets the message's content.

```csharp
[JsonProperty("content", NullValueHandling = NullValueHandling.Ignore)]
public string Content { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessage_EditedTimestamp"></a>EditedTimestamp

Gets the message's edit timestamp. Will be null if the message was not edited.

```csharp
[JsonProperty("edited_timestamp", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? EditedTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordMessage_Embeds"></a>Embeds

Gets embeds attached to this message.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordEmbed> Embeds { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_Flags"></a>Flags

Gets the bitwise flags for this message.

```csharp
[JsonProperty("flags", NullValueHandling = NullValueHandling.Ignore)]
public MessageFlags? Flags { get; }
```

#### Property Value

[MessageFlags](DSharpPlus.MessageFlags.md)?

### <a id="DSharpPlus_Entities_DiscordMessage_Interaction"></a>Interaction

Gets whether the message is a response to an interaction.

```csharp
[JsonProperty("interaction", NullValueHandling = NullValueHandling.Ignore)]
public DiscordMessageInteraction Interaction { get; }
```

#### Property Value

[DiscordMessageInteraction](DSharpPlus.Entities.DiscordMessageInteraction.md)

### <a id="DSharpPlus_Entities_DiscordMessage_IsEdited"></a>IsEdited

Gets whether this message was edited.

```csharp
[JsonIgnore]
public bool IsEdited { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMessage_IsTTS"></a>IsTTS

Gets whether the message is a text-to-speech message.

```csharp
[JsonProperty("tts", NullValueHandling = NullValueHandling.Ignore)]
public bool IsTTS { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMessage_JumpLink"></a>JumpLink

Gets the jump link to this message.

```csharp
[JsonIgnore]
public Uri JumpLink { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

### <a id="DSharpPlus_Entities_DiscordMessage_MentionEveryone"></a>MentionEveryone

Gets whether the message mentions everyone.

```csharp
[JsonProperty("mention_everyone", NullValueHandling = NullValueHandling.Ignore)]
public bool MentionEveryone { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMessage_MentionedChannels"></a>MentionedChannels

Gets channels mentioned by this message.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordChannel> MentionedChannels { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_MentionedRoles"></a>MentionedRoles

Gets roles mentioned by this message.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordRole> MentionedRoles { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_MentionedUsers"></a>MentionedUsers

Gets users or members mentioned by this message.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordUser> MentionedUsers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_MessageType"></a>MessageType

Gets the type of the message.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public MessageType? MessageType { get; }
```

#### Property Value

[MessageType](DSharpPlus.MessageType.md)?

### <a id="DSharpPlus_Entities_DiscordMessage_Pinned"></a>Pinned

Gets whether the message is pinned.

```csharp
[JsonProperty("pinned", NullValueHandling = NullValueHandling.Ignore)]
public bool Pinned { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMessage_Reactions"></a>Reactions

Gets reactions used on this message.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordReaction> Reactions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordReaction](DSharpPlus.Entities.DiscordReaction.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_Reference"></a>Reference

Gets the original message reference from the crossposted message.

```csharp
[JsonIgnore]
public DiscordMessageReference Reference { get; }
```

#### Property Value

[DiscordMessageReference](DSharpPlus.Entities.DiscordMessageReference.md)

### <a id="DSharpPlus_Entities_DiscordMessage_ReferencedMessage"></a>ReferencedMessage

Gets the message object for the referenced message

```csharp
[JsonProperty("referenced_message", NullValueHandling = NullValueHandling.Ignore)]
public DiscordMessage ReferencedMessage { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

### <a id="DSharpPlus_Entities_DiscordMessage_Stickers"></a>Stickers

Gets stickers for this message.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordMessageSticker> Stickers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_Entities_DiscordMessage_Timestamp"></a>Timestamp

Gets the message's creation timestamp.

```csharp
[JsonIgnore]
public DateTimeOffset Timestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordMessage_WebhookId"></a>WebhookId

Gets the id of the webhook that generated this message.

```csharp
[JsonProperty("webhook_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? WebhookId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordMessage_WebhookMessage"></a>WebhookMessage

Gets whether the message originated from a webhook.

```csharp
[JsonIgnore]
public bool WebhookMessage { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="DSharpPlus_Entities_DiscordMessage_CreateReactionAsync_DSharpPlus_Entities_DiscordEmoji_"></a>CreateReactionAsync\(DiscordEmoji\)

Creates a reaction to this message.

```csharp
public Task CreateReactionAsync(DiscordEmoji emoji)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji you want to react with, either an emoji or name:id

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AddReactions" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_CreateThreadAsync_System_String_DSharpPlus_AutoArchiveDuration_System_String_"></a>CreateThreadAsync\(string, AutoArchiveDuration, string\)

Creates a new thread within this channel from this message.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(string name, AutoArchiveDuration archiveAfter, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration of the thread. Three and seven day archive options are locked behind level 2 and level 3 server boosts respectively.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

The created thread.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_DeleteAllReactionsAsync_System_String_"></a>DeleteAllReactionsAsync\(string\)

Deletes all reactions for this message.

```csharp
public Task DeleteAllReactionsAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_DeleteAsync_System_String_"></a>DeleteAsync\(string\)

Deletes the message.

```csharp
public Task DeleteAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_DeleteOwnReactionAsync_DSharpPlus_Entities_DiscordEmoji_"></a>DeleteOwnReactionAsync\(DiscordEmoji\)

Deletes your own reaction

```csharp
public Task DeleteOwnReactionAsync(DiscordEmoji emoji)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji for the reaction you want to remove, either an emoji or name:id

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_DeleteReactionAsync_DSharpPlus_Entities_DiscordEmoji_DSharpPlus_Entities_DiscordUser_System_String_"></a>DeleteReactionAsync\(DiscordEmoji, DiscordUser, string\)

Deletes another user's reaction.

```csharp
public Task DeleteReactionAsync(DiscordEmoji emoji, DiscordUser user, string reason = null)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji for the reaction you want to remove, either an emoji or name:id.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

Member you want to remove the reaction for

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_DeleteReactionsEmojiAsync_DSharpPlus_Entities_DiscordEmoji_"></a>DeleteReactionsEmojiAsync\(DiscordEmoji\)

Deletes all reactions of a specific reaction for this message.

```csharp
public Task DeleteReactionsEmojiAsync(DiscordEmoji emoji)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to clear, either an emoji or name:id.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordMessage_Equals_DSharpPlus_Entities_DiscordMessage_"></a>Equals\(DiscordMessage\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordMessage e)
```

#### Parameters

`e` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

<xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordMessage_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordMessage_GetReactionsAsync_DSharpPlus_Entities_DiscordEmoji_System_Int32_System_Nullable_System_UInt64__"></a>GetReactionsAsync\(DiscordEmoji, int, ulong?\)

Gets users that reacted with this emoji.

```csharp
public Task<IReadOnlyList<DiscordUser>> GetReactionsAsync(DiscordEmoji emoji, int limit = 25, ulong? after = null)
```

#### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji to react with.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit of users to fetch.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users after this user's id.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_System_String__"></a>ModifyAsync\(Optional<string\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<string> content)
```

#### Parameters

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New content.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordEmbed__"></a>ModifyAsync\(Optional<DiscordEmbed\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<DiscordEmbed> embed = default)
```

#### Parameters

`embed` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

New embed.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordEmbed__"></a>ModifyAsync\(Optional<string\>, Optional<DiscordEmbed\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<string> content, Optional<DiscordEmbed> embed = default)
```

#### Parameters

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New content.

`embed` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

New embed.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmbed___"></a>ModifyAsync\(Optional<string\>, Optional<IEnumerable<DiscordEmbed\>\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<string> content, Optional<IEnumerable<DiscordEmbed>> embeds = default)
```

#### Parameters

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New content.

`embeds` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>\>

New embeds.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_DiscordMessageBuilder_System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>ModifyAsync\(DiscordMessageBuilder, bool, IEnumerable<DiscordAttachment\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordMessageBuilder builder, bool suppressEmbeds = false, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The builder of the message to edit.

`suppressEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to suppress embeds on the message.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>ModifyAsync\(Action<DiscordMessageBuilder\>, bool, IEnumerable<DiscordAttachment\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Action<DiscordMessageBuilder> action, bool suppressEmbeds = false, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The builder of the message to edit.

`suppressEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to suppress embeds on the message.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ModifyEmbedSuppressionAsync_System_Boolean_"></a>ModifyEmbedSuppressionAsync\(bool\)

Modifies the visibility of embeds in this message.

```csharp
public Task ModifyEmbedSuppressionAsync(bool hideEmbeds)
```

#### Parameters

`hideEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to hide all embeds.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_PinAsync"></a>PinAsync\(\)

Pins the message in its channel.

```csharp
public Task PinAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_RespondAsync_System_String_"></a>RespondAsync\(string\)

Responds to the message. This produces a reply.

```csharp
public Task<DiscordMessage> RespondAsync(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message content to respond with.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_RespondAsync_DSharpPlus_Entities_DiscordEmbed_"></a>RespondAsync\(DiscordEmbed\)

Responds to the message. This produces a reply.

```csharp
public Task<DiscordMessage> RespondAsync(DiscordEmbed embed)
```

#### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_RespondAsync_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>RespondAsync\(string, DiscordEmbed\)

Responds to the message. This produces a reply.

```csharp
public Task<DiscordMessage> RespondAsync(string content, DiscordEmbed embed)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message content to respond with.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_RespondAsync_DSharpPlus_Entities_DiscordMessageBuilder_"></a>RespondAsync\(DiscordMessageBuilder\)

Responds to the message. This produces a reply.

```csharp
public Task<DiscordMessage> RespondAsync(DiscordMessageBuilder builder)
```

#### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The Discord message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_RespondAsync_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>RespondAsync\(Action<DiscordMessageBuilder\>\)

Responds to the message. This produces a reply.

```csharp
public Task<DiscordMessage> RespondAsync(Action<DiscordMessageBuilder> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The Discord message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMessage_ToString"></a>ToString\(\)

Returns a string representation of this message.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this message.

### <a id="DSharpPlus_Entities_DiscordMessage_UnpinAsync"></a>UnpinAsync\(\)

Unpins the message in its channel.

```csharp
public Task UnpinAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## Operators

### <a id="DSharpPlus_Entities_DiscordMessage_op_Equality_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordMessage_"></a>operator ==\(DiscordMessage, DiscordMessage\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordMessage e1, DiscordMessage e2)
```

#### Parameters

`e1` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

First message to compare.

`e2` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Second message to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two messages are equal.

### <a id="DSharpPlus_Entities_DiscordMessage_op_Inequality_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordMessage_"></a>operator \!=\(DiscordMessage, DiscordMessage\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordMessage e1, DiscordMessage e2)
```

#### Parameters

`e1` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

First message to compare.

`e2` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Second message to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two messages are not equal.

