# Class DiscordInteraction

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an interaction that was invoked.

```csharp
public sealed class DiscordInteraction : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordInteraction](DSharpPlus.Entities.DiscordInteraction.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

###### Extension Methods

[InteractionExtensions.SendPaginatedResponseAsync\(DiscordInteraction, bool, DiscordUser, IEnumerable<Page\>, PaginationButtons, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken, bool\)](DSharpPlus.Interactivity.Extensions.InteractionExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_InteractionExtensions\_SendPaginatedResponseAsync\_DSharpPlus\_Entities\_DiscordInteraction\_System\_Boolean\_DSharpPlus\_Entities\_DiscordUser\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Interactivity\_Page\_\_DSharpPlus\_Interactivity\_EventHandling\_PaginationButtons\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PaginationBehaviour\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_ButtonPaginationBehavior\_\_System\_Threading\_CancellationToken\_System\_Boolean\_)

## Properties

### <a id="DSharpPlus_Entities_DiscordInteraction_ApplicationId"></a>ApplicationId

Gets the ID of the application that created this interaction.

```csharp
[JsonProperty("application_id")]
public ulong ApplicationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordInteraction_Channel"></a>Channel

Gets the channel that invoked this interaction.

```csharp
[JsonIgnore]
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordInteraction_ChannelId"></a>ChannelId

Gets the Id of the channel that invoked this interaction.

```csharp
[JsonProperty("channel_id")]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordInteraction_Data"></a>Data

Gets the command data for this interaction.

```csharp
[JsonProperty("data", NullValueHandling = NullValueHandling.Ignore)]
public DiscordInteractionData Data { get; }
```

#### Property Value

[DiscordInteractionData](DSharpPlus.Entities.DiscordInteractionData.md)

### <a id="DSharpPlus_Entities_DiscordInteraction_Guild"></a>Guild

Gets the guild that invoked this interaction.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordInteraction_GuildId"></a>GuildId

Gets the Id of the guild that invoked this interaction.

```csharp
[JsonIgnore]
public ulong? GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordInteraction_GuildLocale"></a>GuildLocale

Gets the guild's preferred locale, if invoked in a guild.

```csharp
[JsonProperty("guild_locale")]
public string? GuildLocale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordInteraction_Locale"></a>Locale

Gets the locale of the user that invoked this interaction.

```csharp
[JsonProperty("locale")]
public string? Locale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordInteraction_Token"></a>Token

Gets the continuation token for responding to this interaction.

```csharp
[JsonProperty("token")]
public string Token { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInteraction_Type"></a>Type

Gets the type of interaction invoked.

```csharp
[JsonProperty("type")]
public InteractionType Type { get; }
```

#### Property Value

[InteractionType](DSharpPlus.InteractionType.md)

### <a id="DSharpPlus_Entities_DiscordInteraction_User"></a>User

Gets the user that invoked this interaction.
<p>This can be cast to a <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> if created in a guild.</p>

```csharp
[JsonIgnore]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_Entities_DiscordInteraction_Version"></a>Version

Gets the version number for this interaction type.

```csharp
[JsonProperty("version")]
public int Version { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_Entities_DiscordInteraction_CreateFollowupMessageAsync_DSharpPlus_Entities_DiscordFollowupMessageBuilder_"></a>CreateFollowupMessageAsync\(DiscordFollowupMessageBuilder\)

Creates a follow up message to this interaction.

```csharp
public Task<DiscordMessage> CreateFollowupMessageAsync(DiscordFollowupMessageBuilder builder)
```

#### Parameters

`builder` [DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

The webhook builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> created.

### <a id="DSharpPlus_Entities_DiscordInteraction_CreateResponseAsync_DSharpPlus_InteractionResponseType_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateResponseAsync\(InteractionResponseType, DiscordInteractionResponseBuilder\)

Creates a response to this interaction.

```csharp
public Task CreateResponseAsync(InteractionResponseType type, DiscordInteractionResponseBuilder builder = null)
```

#### Parameters

`type` [InteractionResponseType](DSharpPlus.InteractionResponseType.md)

The type of the response.

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data, if any, to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordInteraction_DeferAsync_System_Boolean_"></a>DeferAsync\(bool\)

Creates a deferred response to this interaction.

```csharp
public Task DeferAsync(bool ephemeral = false)
```

#### Parameters

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordInteraction_DeleteFollowupMessageAsync_System_UInt64_"></a>DeleteFollowupMessageAsync\(ulong\)

Deletes a follow up message.

```csharp
public Task DeleteFollowupMessageAsync(ulong messageId)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the follow up message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordInteraction_DeleteOriginalResponseAsync"></a>DeleteOriginalResponseAsync\(\)

Deletes the original interaction response.

```csharp
public Task DeleteOriginalResponseAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordInteraction_EditFollowupMessageAsync_System_UInt64_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditFollowupMessageAsync\(ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits a follow up message.

```csharp
public Task<DiscordMessage> EditFollowupMessageAsync(ulong messageId, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the follow up message.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The webhook builder.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> edited.

### <a id="DSharpPlus_Entities_DiscordInteraction_EditOriginalResponseAsync_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditOriginalResponseAsync\(DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits the original interaction response.

```csharp
public Task<DiscordMessage> EditOriginalResponseAsync(DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The webhook builder.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> edited.

### <a id="DSharpPlus_Entities_DiscordInteraction_GetFollowupMessageAsync_System_UInt64_"></a>GetFollowupMessageAsync\(ulong\)

Gets a follow up message.

```csharp
public Task<DiscordMessage> GetFollowupMessageAsync(ulong messageId)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the follow up message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_Entities_DiscordInteraction_GetOriginalResponseAsync"></a>GetOriginalResponseAsync\(\)

Gets the original interaction response.

```csharp
public Task<DiscordMessage> GetOriginalResponseAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The original message that was sent.

