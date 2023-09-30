# Class DiscordMessageBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Constructs a Message to be sent.

```csharp
public sealed class DiscordMessageBuilder : BaseDiscordMessageBuilder<DiscordMessageBuilder>, IDiscordMessageBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md) ← 
[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

###### Implements

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

###### Inherited Members

[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Content](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Content), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Flags](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Flags), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.SuppressNotifications\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_SuppressNotifications), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.IsTTS](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_IsTTS), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Embeds](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Embeds), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Files](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Files), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Mentions](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Mentions), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Components](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Components), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.WithContent\(string\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithContent\_System\_String\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddComponents\(params DiscordComponent\[\]\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_DSharpPlus\_Entities\_DiscordComponent\_\_\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddComponents\(IEnumerable<DiscordActionRowComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordActionRowComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddComponents\(IEnumerable<DiscordComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.WithTTS\(bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithTTS\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddEmbed\(DiscordEmbed\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbed\_DSharpPlus\_Entities\_DiscordEmbed\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddEmbeds\(IEnumerable<DiscordEmbed\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbeds\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordEmbed\_\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddFile\(string, Stream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddFile\(FileStream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddFiles\(IDictionary<string, Stream\>, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddFile\(string, Stream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddFile\(FileStream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddFiles\(IEnumerable<DiscordMessageFile\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordMessageFile\_\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddMention\(IMention\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMention\_DSharpPlus\_Entities\_IMention\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.AddMentions\(IEnumerable<IMention\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMentions\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_IMention\_\_), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.ClearComponents\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_ClearComponents), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Clear\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Clear), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.Dispose\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Dispose), 
[BaseDiscordMessageBuilder<DiscordMessageBuilder\>.DisposeAsync\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_DisposeAsync)

## Constructors

### <a id="DSharpPlus_Entities_DiscordMessageBuilder__ctor"></a>DiscordMessageBuilder\(\)

Constructs a new discord message builder

```csharp
public DiscordMessageBuilder()
```

### <a id="DSharpPlus_Entities_DiscordMessageBuilder__ctor_DSharpPlus_Entities_DiscordMessageBuilder_"></a>DiscordMessageBuilder\(DiscordMessageBuilder\)

Constructs a new discord message builder based on a previous builder.

```csharp
public DiscordMessageBuilder(DiscordMessageBuilder builder)
```

#### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The builder to copy.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder__ctor_DSharpPlus_Entities_IDiscordMessageBuilder_"></a>DiscordMessageBuilder\(IDiscordMessageBuilder\)

Copies the common properties from the passed builder.

```csharp
public DiscordMessageBuilder(IDiscordMessageBuilder builder)
```

#### Parameters

`builder` [IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

The builder to copy.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder__ctor_DSharpPlus_Entities_DiscordMessage_"></a>DiscordMessageBuilder\(DiscordMessage\)

Constructs a new discord message builder based on the passed message.

```csharp
public DiscordMessageBuilder(DiscordMessage baseMessage)
```

#### Parameters

`baseMessage` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to copy.

## Properties

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_Embed"></a>Embed

Gets or sets the embed for the builder. This will always set the builder to have one embed.

```csharp
public DiscordEmbed Embed { get; set; }
```

#### Property Value

[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_FailOnInvalidReply"></a>FailOnInvalidReply

Gets if the Reply will error if the Reply Message Id does not reference a valid message.
<p>If set to false, invalid replies are send as a regular message.</p>
<p>Defaults to false.</p>

```csharp
public bool FailOnInvalidReply { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_MentionOnReply"></a>MentionOnReply

Gets if the Reply should mention the user.

```csharp
public bool MentionOnReply { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_ReplyId"></a>ReplyId

Gets the Reply Message ID.

```csharp
public ulong? ReplyId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_Sticker"></a>Sticker

Gets or sets the sticker for the builder. This will always set the builder to have one sticker.

```csharp
public DiscordMessageSticker Sticker { get; set; }
```

#### Property Value

[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_Stickers"></a>Stickers

The stickers to attach to the message.

```csharp
public IReadOnlyList<DiscordMessageSticker> Stickers { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

## Methods

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_ClearComponents"></a>ClearComponents\(\)

Clears all message components on this builder.

```csharp
public override void ClearComponents()
```

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_ModifyAsync_DSharpPlus_Entities_DiscordMessage_"></a>ModifyAsync\(DiscordMessage\)

Sends the modified message.
<p>Note: Message replies cannot be modified. To clear the reply, simply pass <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> to <xref href="DSharpPlus.Entities.DiscordMessageBuilder.WithReply(System.Nullable%7bSystem.UInt64%7d%2cSystem.Boolean%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordMessage msg)
```

#### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The original Message to modify.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The current builder to be chained.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_SendAsync_DSharpPlus_Entities_DiscordChannel_"></a>SendAsync\(DiscordChannel\)

Sends the Message to a specific channel

```csharp
public Task<DiscordMessage> SendAsync(DiscordChannel channel)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel the message should be sent to.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The current builder to be chained.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_WithAllowedMention_DSharpPlus_Entities_IMention_"></a>WithAllowedMention\(IMention\)

Sets if the message has allowed mentions.

```csharp
public DiscordMessageBuilder WithAllowedMention(IMention allowedMention)
```

#### Parameters

`allowedMention` [IMention](DSharpPlus.Entities.IMention.md)

The allowed Mention that should be sent.

#### Returns

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The current builder to be chained.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_WithAllowedMentions_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_IMention__"></a>WithAllowedMentions\(IEnumerable<IMention\>\)

Sets if the message has allowed mentions.

```csharp
public DiscordMessageBuilder WithAllowedMentions(IEnumerable<IMention> allowedMentions)
```

#### Parameters

`allowedMentions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[IMention](DSharpPlus.Entities.IMention.md)\>

The allowed Mentions that should be sent.

#### Returns

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The current builder to be chained.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_WithEmbed_DSharpPlus_Entities_DiscordEmbed_"></a>WithEmbed\(DiscordEmbed\)

Sets the embed for the current builder.

```csharp
public DiscordMessageBuilder WithEmbed(DiscordEmbed embed)
```

#### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

The embed that should be set.

#### Returns

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The current builder to be chained.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_WithReply_System_Nullable_System_UInt64__System_Boolean_System_Boolean_"></a>WithReply\(ulong?, bool, bool\)

Sets if the message is a reply

```csharp
public DiscordMessageBuilder WithReply(ulong? messageId, bool mention = false, bool failOnInvalidReply = false)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the message to reply to.

`mention` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

If we should mention the user in the reply.

`failOnInvalidReply` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether sending a reply that references an invalid message should be

#### Returns

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The current builder to be chained.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_WithSticker_DSharpPlus_Entities_DiscordMessageSticker_"></a>WithSticker\(DiscordMessageSticker\)

Adds a sticker to the message. Sticker must be from current guild.

```csharp
public DiscordMessageBuilder WithSticker(DiscordMessageSticker sticker)
```

#### Parameters

`sticker` [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

The sticker to add.

#### Returns

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The current builder to be chained.

### <a id="DSharpPlus_Entities_DiscordMessageBuilder_WithStickers_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordMessageSticker__"></a>WithStickers\(IEnumerable<DiscordMessageSticker\>\)

Adds a sticker to the message. Sticker must be from current guild.

```csharp
public DiscordMessageBuilder WithStickers(IEnumerable<DiscordMessageSticker> stickers)
```

#### Parameters

`stickers` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

The sticker to add.

#### Returns

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The current builder to be chained.

