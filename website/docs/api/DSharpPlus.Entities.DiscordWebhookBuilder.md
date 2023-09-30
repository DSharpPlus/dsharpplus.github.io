# Class DiscordWebhookBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Constructs ready-to-send webhook requests.

```csharp
public sealed class DiscordWebhookBuilder : BaseDiscordMessageBuilder<DiscordWebhookBuilder>, IDiscordMessageBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md) ← 
[DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

###### Implements

[IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

###### Inherited Members

[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Content](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Content), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Flags](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Flags), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.SuppressNotifications\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_SuppressNotifications), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.IsTTS](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_IsTTS), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Embeds](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Embeds), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Files](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Files), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Mentions](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Mentions), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Components](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Components), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.WithContent\(string\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithContent\_System\_String\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddComponents\(params DiscordComponent\[\]\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_DSharpPlus\_Entities\_DiscordComponent\_\_\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddComponents\(IEnumerable<DiscordActionRowComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordActionRowComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddComponents\(IEnumerable<DiscordComponent\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddComponents\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordComponent\_\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.WithTTS\(bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_WithTTS\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddEmbed\(DiscordEmbed\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbed\_DSharpPlus\_Entities\_DiscordEmbed\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddEmbeds\(IEnumerable<DiscordEmbed\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddEmbeds\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordEmbed\_\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddFile\(string, Stream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddFile\(FileStream, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddFiles\(IDictionary<string, Stream\>, bool\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_System\_Boolean\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddFile\(string, Stream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_String\_System\_IO\_Stream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddFile\(FileStream, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFile\_System\_IO\_FileStream\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddFiles\(IDictionary<string, Stream\>, AddFileOptions\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IDictionary\_System\_String\_System\_IO\_Stream\_\_DSharpPlus\_Entities\_AddFileOptions\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddFiles\(IEnumerable<DiscordMessageFile\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddFiles\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordMessageFile\_\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddMention\(IMention\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMention\_DSharpPlus\_Entities\_IMention\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.AddMentions\(IEnumerable<IMention\>\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_AddMentions\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_IMention\_\_), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.ClearComponents\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_ClearComponents), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Clear\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Clear), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.Dispose\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_Dispose), 
[BaseDiscordMessageBuilder<DiscordWebhookBuilder\>.DisposeAsync\(\)](DSharpPlus.Entities.BaseDiscordMessageBuilder\-1.md\#DSharpPlus\_Entities\_BaseDiscordMessageBuilder\_1\_DisposeAsync)

## Constructors

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder__ctor"></a>DiscordWebhookBuilder\(\)

Constructs a new empty webhook request builder.

```csharp
public DiscordWebhookBuilder()
```

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder__ctor_DSharpPlus_Entities_DiscordWebhookBuilder_"></a>DiscordWebhookBuilder\(DiscordWebhookBuilder\)

Constructs a new webhook request builder based on a previous message builder

```csharp
public DiscordWebhookBuilder(DiscordWebhookBuilder builder)
```

#### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The builder to copy.

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder__ctor_DSharpPlus_Entities_IDiscordMessageBuilder_"></a>DiscordWebhookBuilder\(IDiscordMessageBuilder\)

Copies the common properties from the passed builder.

```csharp
public DiscordWebhookBuilder(IDiscordMessageBuilder builder)
```

#### Parameters

`builder` [IDiscordMessageBuilder](DSharpPlus.Entities.IDiscordMessageBuilder.md)

The builder to copy.

## Properties

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_AvatarUrl"></a>AvatarUrl

Avatar url to use for this webhook request.

```csharp
public Optional<string> AvatarUrl { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_ThreadId"></a>ThreadId

Id of the thread to send the webhook request to.

```csharp
public ulong? ThreadId { get; set; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_Username"></a>Username

Username to use for this webhook request.

```csharp
public Optional<string> Username { get; set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

## Methods

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_Clear"></a>Clear\(\)

Allows for clearing the Message Builder so that it can be used again to send a new message.

```csharp
public override void Clear()
```

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_ModifyAsync_DSharpPlus_Entities_DiscordWebhook_DSharpPlus_Entities_DiscordMessage_"></a>ModifyAsync\(DiscordWebhook, DiscordMessage\)

Sends the modified webhook message.

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordWebhook webhook, DiscordMessage message)
```

#### Parameters

`webhook` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The webhook that should be executed.

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to modify.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The modified message

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_ModifyAsync_DSharpPlus_Entities_DiscordWebhook_System_UInt64_"></a>ModifyAsync\(DiscordWebhook, ulong\)

Sends the modified webhook message.

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordWebhook webhook, ulong messageId)
```

#### Parameters

`webhook` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The webhook that should be executed.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the message to modify.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The modified message

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_SendAsync_DSharpPlus_Entities_DiscordWebhook_"></a>SendAsync\(DiscordWebhook\)

Executes a webhook.

```csharp
public Task<DiscordMessage> SendAsync(DiscordWebhook webhook)
```

#### Parameters

`webhook` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The webhook that should be executed.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The message sent

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_WithAvatarUrl_System_String_"></a>WithAvatarUrl\(string\)

Sets the avatar of this webhook builder from its url.

```csharp
public DiscordWebhookBuilder WithAvatarUrl(string avatarUrl)
```

#### Parameters

`avatarUrl` [string](https://learn.microsoft.com/dotnet/api/system.string)

Avatar url of the webhook

#### Returns

[DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_WithThreadId_System_Nullable_System_UInt64__"></a>WithThreadId\(ulong?\)

Sets the id of the thread to execute the webhook on.

```csharp
public DiscordWebhookBuilder WithThreadId(ulong? threadId)
```

#### Parameters

`threadId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The id of the thread

#### Returns

[DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

### <a id="DSharpPlus_Entities_DiscordWebhookBuilder_WithUsername_System_String_"></a>WithUsername\(string\)

Sets the username for this webhook builder.

```csharp
public DiscordWebhookBuilder WithUsername(string username)
```

#### Parameters

`username` [string](https://learn.microsoft.com/dotnet/api/system.string)

Username of the webhook

#### Returns

[DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

