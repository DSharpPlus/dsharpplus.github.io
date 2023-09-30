# Class BaseDiscordMessageBuilder<T\>

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Interface that provides abstractions for the various message builder types in DSharpPlus,
allowing re-use of code.

```csharp
public abstract class BaseDiscordMessageBuilder<T> : IDiscordMessageBuilder where T : BaseDiscordMessageBuilder<T>
```

#### Type Parameters

`T` 

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordMessageBuilder<T\>](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md)

###### Implements

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

## Constructors

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1__ctor_DSharpPlus_Entities_IDiscordMessageBuilder_"></a>BaseDiscordMessageBuilder\(IDiscordMessageBuilder\)

Constructs a new <xref href="DSharpPlus.Entities.BaseDiscordMessageBuilder%601" data-throw-if-not-resolved="false"></xref> based on an existing <xref href="DSharpPlus.Entities.IDiscordMessageBuilder" data-throw-if-not-resolved="false"></xref>.
Existing file streams will have their position reset to 0.

```csharp
protected BaseDiscordMessageBuilder(IDiscordMessageBuilder builder)
```

#### Parameters

`builder` [IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

The builder to copy.

## Properties

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Components"></a>Components

Components to send on this followup message.

```csharp
public IReadOnlyList<DiscordActionRowComponent> Components { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Content"></a>Content

Message to send on this webhook request.

```csharp
public string Content { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Embeds"></a>Embeds

Embeds to send on this webhook request.

```csharp
public IReadOnlyList<DiscordEmbed> Embeds { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Files"></a>Files

Files to send on this webhook request.

```csharp
public IReadOnlyList<DiscordMessageFile> Files { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageFile](DSharpPlus.Entities.DiscordMessageFile.md)\>

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Flags"></a>Flags

```csharp
public MessageFlags Flags { get; }
```

#### Property Value

[MessageFlags](DSharpPlus.MessageFlags.md)

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_IsTTS"></a>IsTTS

Whether this message will play as a text-to-speech message.

```csharp
public bool IsTTS { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Mentions"></a>Mentions

Mentions to send on this webhook request.

```csharp
public IReadOnlyList<IMention> Mentions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[IMention](DSharpPlus.Entities.IMention.md)\>

## Methods

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddComponents_DSharpPlus_Entities_DiscordComponent___"></a>AddComponents\(params DiscordComponent\[\]\)

Adds a row of components to a message, up to 5 components per row, and up to 5 rows per message.

```csharp
public T AddComponents(params DiscordComponent[] components)
```

#### Parameters

`components` [DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\[\]

The components to add to the message.

#### Returns

T

The current builder to be chained.

#### Exceptions

[ArgumentOutOfRangeException](https://learn.microsoft.com/dotnet/api/system.argumentoutofrangeexception)

No components were passed.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordActionRowComponent__"></a>AddComponents\(IEnumerable<DiscordActionRowComponent\>\)

Appends several rows of components to the message

```csharp
public T AddComponents(IEnumerable<DiscordActionRowComponent> components)
```

#### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)\>

The rows of components to add, holding up to five each.

#### Returns

T

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddComponents_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordComponent__"></a>AddComponents\(IEnumerable<DiscordComponent\>\)

Adds a row of components to a message, up to 5 components per row, and up to 5 rows per message.

```csharp
public T AddComponents(IEnumerable<DiscordComponent> components)
```

#### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\>

The components to add to the message.

#### Returns

T

The current builder to be chained.

#### Exceptions

[ArgumentOutOfRangeException](https://learn.microsoft.com/dotnet/api/system.argumentoutofrangeexception)

No components were passed.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddEmbed_DSharpPlus_Entities_DiscordEmbed_"></a>AddEmbed\(DiscordEmbed\)

Appends an embed to the current builder.

```csharp
public T AddEmbed(DiscordEmbed embed)
```

#### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

The embed that should be appended.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddEmbeds_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmbed__"></a>AddEmbeds\(IEnumerable<DiscordEmbed\>\)

Appends several embeds to the current builder.

```csharp
public T AddEmbeds(IEnumerable<DiscordEmbed> embeds)
```

#### Parameters

`embeds` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

The embeds that should be appended.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_String_System_IO_Stream_System_Boolean_"></a>AddFile\(string, Stream, bool\)

Sets if the message has files to be sent.

```csharp
public T AddFile(string fileName, Stream stream, bool resetStreamPosition = false)
```

#### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

The fileName that the file should be sent as.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The Stream to the file.

`resetStreamPosition` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Tells the API Client to reset the stream position to what it was after the file is sent.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_IO_FileStream_System_Boolean_"></a>AddFile\(FileStream, bool\)

Sets if the message has files to be sent.

```csharp
public T AddFile(FileStream stream, bool resetStreamPosition = false)
```

#### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

The Stream to the file.

`resetStreamPosition` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Tells the API Client to reset the stream position to what it was after the file is sent.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_String_System_IO_Stream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(string, Stream, AddFileOptions\)

Attaches a file to this message.

```csharp
public T AddFile(string fileName, Stream stream, AddFileOptions fileOptions)
```

#### Parameters

`fileName` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the file to attach.

`stream` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Stream containing said file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFile_System_IO_FileStream_DSharpPlus_Entities_AddFileOptions_"></a>AddFile\(FileStream, AddFileOptions\)

Attaches a file to this message.

```csharp
public T AddFile(FileStream stream, AddFileOptions fileOptions)
```

#### Parameters

`stream` [FileStream](https://learn.microsoft.com/dotnet/api/system.io.filestream)

FileStream pointing to the file to attach.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file stream.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__System_Boolean_"></a>AddFiles\(IDictionary<string, Stream\>, bool\)

Sets if the message has files to be sent.

```csharp
public T AddFiles(IDictionary<string, Stream> files, bool resetStreamPosition = false)
```

#### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

The Files that should be sent.

`resetStreamPosition` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Tells the API Client to reset the stream position to what it was after the file is sent.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFiles_System_Collections_Generic_IDictionary_System_String_System_IO_Stream__DSharpPlus_Entities_AddFileOptions_"></a>AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)

Attaches multiple files to this message.

```csharp
public T AddFiles(IDictionary<string, Stream> files, AddFileOptions fileOptions)
```

#### Parameters

`files` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Dictionary of files to add, where <xref href="System.String" data-throw-if-not-resolved="false"></xref> is a file name and <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> is a stream containing the file's contents.

`fileOptions` [AddFileOptions](DSharpPlus.Entities.AddFileOptions.md)

Additional flags for the handling of the file streams.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddFiles_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordMessageFile__"></a>AddFiles\(IEnumerable<DiscordMessageFile\>\)

```csharp
public T AddFiles(IEnumerable<DiscordMessageFile> files)
```

#### Parameters

`files` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordMessageFile](DSharpPlus.Entities.DiscordMessageFile.md)\>

#### Returns

T

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddMention_DSharpPlus_Entities_IMention_"></a>AddMention\(IMention\)

Adds the mention to the mentions to parse, etc. with the interaction response.

```csharp
public T AddMention(IMention mention)
```

#### Parameters

`mention` [IMention](DSharpPlus.Entities.IMention.md)

Mention to add.

#### Returns

T

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_AddMentions_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_IMention__"></a>AddMentions\(IEnumerable<IMention\>\)

Adds the mentions to the mentions to parse, etc. with the interaction response.

```csharp
public T AddMentions(IEnumerable<IMention> mentions)
```

#### Parameters

`mentions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[IMention](DSharpPlus.Entities.IMention.md)\>

Mentions to add.

#### Returns

T

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Clear"></a>Clear\(\)

Allows for clearing the Message Builder so that it can be used again to send a new message.

```csharp
public virtual void Clear()
```

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_ClearComponents"></a>ClearComponents\(\)

Clears all message components on this builder.

```csharp
public virtual void ClearComponents()
```

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_Dispose"></a>Dispose\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

```csharp
public void Dispose()
```

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_DisposeAsync"></a>DisposeAsync\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources asynchronously.

```csharp
public ValueTask DisposeAsync()
```

#### Returns

[ValueTask](https://learn.microsoft.com/dotnet/api/system.threading.tasks.valuetask)

A task that represents the asynchronous dispose operation.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_SuppressNotifications"></a>SuppressNotifications\(\)

```csharp
public T SuppressNotifications()
```

#### Returns

T

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_WithContent_System_String_"></a>WithContent\(string\)

Sets the Content of the Message.

```csharp
public T WithContent(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

The content to be set.

#### Returns

T

The current builder to be chained.

### <a id="DSharpPlus_Entities_BaseDiscordMessageBuilder_1_WithTTS_System_Boolean_"></a>WithTTS\(bool\)

Sets if the message should be TTS.

```csharp
public T WithTTS(bool isTTS)
```

#### Parameters

`isTTS` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

If TTS should be set.

#### Returns

T

The current builder to be chained.

