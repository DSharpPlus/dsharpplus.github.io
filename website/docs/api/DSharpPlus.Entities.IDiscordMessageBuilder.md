# Interface IDiscordMessageBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Base interface for any discord message builder.

```csharp
public interface IDiscordMessageBuilder
```

## Properties

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_Components"></a>Components

All components on this message.

```csharp
IReadOnlyList<DiscordActionRowComponent> Components { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_Content"></a>Content

Getter / setter for message content.

```csharp
string Content { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_Embeds"></a>Embeds

All embeds on this message.

```csharp
IReadOnlyList<DiscordEmbed> Embeds { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_Files"></a>Files

All files on this message.

```csharp
IReadOnlyList<DiscordMessageFile> Files { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageFile](DSharpPlus.Entities.DiscordMessageFile.md)\>

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_Flags"></a>Flags

```csharp
MessageFlags Flags { get; }
```

#### Property Value

[MessageFlags](DSharpPlus.MessageFlags.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_IsTTS"></a>IsTTS

Whether this message will play as a text-to-speech message.

```csharp
bool IsTTS { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_Mentions"></a>Mentions

All allowed mentions on this message.

```csharp
IReadOnlyList<IMention> Mentions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[IMention](DSharpPlus.Entities.IMention.md)\>

## Methods

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddComponents_DSharpPlus_Entities_DiscordComponent___"></a>AddComponents\(params DiscordComponent\[\]\)

Adds components to this message. Each call should append to a new row.

```csharp
IDiscordMessageBuilder AddComponents(params DiscordComponent[] components)
```

#### Parameters

`components` [DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\[\]

Components to add.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordComponent__"></a>AddComponents\(IEnumerable<DiscordComponent\>\)

Adds components to this message. Each call should append to a new row.

```csharp
IDiscordMessageBuilder AddComponents(IEnumerable<DiscordComponent> components)
```

#### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\>

Components to add.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordActionRowComponent__"></a>AddComponents\(IEnumerable<DiscordActionRowComponent\>\)

Adds an action row component to this message.

```csharp
IDiscordMessageBuilder AddComponents(IEnumerable<DiscordActionRowComponent> components)
```

#### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

Action row to add to this message. Should contain child components.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddEmbed_DSharpPlus_Entities_DiscordEmbed_"></a>AddEmbed\(DiscordEmbed\)

Adds an embed to this message.

```csharp
IDiscordMessageBuilder AddEmbed(DiscordEmbed embed)
```

#### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to add.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddEmbeds_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmbed__"></a>AddEmbeds\(IEnumerable<DiscordEmbed\>\)

Adds multiple embeds to this message.

```csharp
IDiscordMessageBuilder AddEmbeds(IEnumerable<DiscordEmbed> embeds)
```

#### Parameters

`embeds` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

Collection of embeds to add.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_String_System_IO_Stream_System_Boolean_"></a>AddFile\(string, Stream, bool\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(string fileName, Stream stream, bool resetStream = false)
```

#### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the file to attach.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Stream containing said file's contents.

`resetStream` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to reset the stream to position 0 after sending.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_IO_FileStream_System_Boolean_"></a>AddFile\(FileStream, bool\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(FileStream stream, bool resetStream = false)
```

#### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

FileStream pointing to the file to attach.

`resetStream` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to reset the stream position to 0 after sending.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_String_System_IO_Stream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(string, Stream, AddFileOptions\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(string fileName, Stream stream, AddFileOptions fileOptions)
```

#### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the file to attach.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Stream containing said file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFile_System_IO_FileStream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(FileStream, AddFileOptions\)

Attaches a file to this message.

```csharp
IDiscordMessageBuilder AddFile(FileStream stream, AddFileOptions fileOptions)
```

#### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

FileStream pointing to the file to attach.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__System_Boolean_"></a>AddFiles\(IDictionary<string, Stream\>, bool\)

Attaches multiple files to this message.

```csharp
IDiscordMessageBuilder AddFiles(IDictionary<string, Stream> files, bool resetStreams = false)
```

#### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Dictionary of files to add, where <xref href="System.String" data-throw-if-not-resolved="false"></xref> is a file name and <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> is a stream containing the file's contents.

`resetStreams` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to reset all stream positions to 0 after sending.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__DSharpPlus_Entities_AddFileOptions_"></a>AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)

Attaches multiple files to this message.

```csharp
IDiscordMessageBuilder AddFiles(IDictionary<string, Stream> files, AddFileOptions fileOptions)
```

#### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Dictionary of files to add, where <xref href="System.String" data-throw-if-not-resolved="false"></xref> is a file name and <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> is a stream containing the file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file streams.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddFiles_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordMessageFile__"></a>AddFiles\(IEnumerable<DiscordMessageFile\>\)

Attaches previously used files to this file stream.

```csharp
IDiscordMessageBuilder AddFiles(IEnumerable<DiscordMessageFile> files)
```

#### Parameters

`files` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordMessageFile](DSharpPlus.Entities.DiscordMessageFile.md)\>

Previously attached files to reattach

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddMention_DSharpPlus_Entities_IMention_"></a>AddMention\(IMention\)

Adds an allowed mention to this message.

```csharp
IDiscordMessageBuilder AddMention(IMention mention)
```

#### Parameters

`mention` [IMention](DSharpPlus.Entities.IMention.md)

Mention to allow in this message.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_AddMentions_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_IMention__"></a>AddMentions\(IEnumerable<IMention\>\)

Adds multiple allowed mentions to this message.

```csharp
IDiscordMessageBuilder AddMentions(IEnumerable<IMention> mentions)
```

#### Parameters

`mentions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[IMention](DSharpPlus.Entities.IMention.md)\>

Collection of mentions to allow in this message.

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_Clear"></a>Clear\(\)

Clears this builder.

```csharp
void Clear()
```

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_ClearComponents"></a>ClearComponents\(\)

Clears all components attached to this builder.

```csharp
void ClearComponents()
```

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_SuppressNotifications"></a>SuppressNotifications\(\)

Applies <xref href="DSharpPlus.MessageFlags.SupressNotifications" data-throw-if-not-resolved="false"></xref> to the message.

```csharp
IDiscordMessageBuilder SuppressNotifications()
```

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

#### Remarks

As per <xref href="DSharpPlus.MessageFlags.SupressNotifications" data-throw-if-not-resolved="false"></xref>, this does not change the message's allowed mentions
(controlled by <xref href="DSharpPlus.Entities.IDiscordMessageBuilder.AddMentions(System.Collections.Generic.IEnumerable%7bDSharpPlus.Entities.IMention%7d)" data-throw-if-not-resolved="false"></xref>), but instead prevents a mention from triggering a push notification.

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_WithContent_System_String_"></a>WithContent\(string\)

Adds content to this message

```csharp
IDiscordMessageBuilder WithContent(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message content to use

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

### <a id="DSharpPlus_Entities_IDiscordMessageBuilder_WithTTS_System_Boolean_"></a>WithTTS\(bool\)

Sets whether this message should play as a text-to-speech message.

```csharp
IDiscordMessageBuilder WithTTS(bool isTTS)
```

#### Parameters

`isTTS` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

#### Returns

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

