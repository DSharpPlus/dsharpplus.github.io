# Method ModifyAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_System_String__"></a>ModifyAsync\(Optional<string\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<string> content)
```

### Parameters

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New content.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordEmbed__"></a>ModifyAsync\(Optional<DiscordEmbed\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<DiscordEmbed> embed = default)
```

### Parameters

`embed` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

New embed.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordEmbed__"></a>ModifyAsync\(Optional<string\>, Optional<DiscordEmbed\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<string> content, Optional<DiscordEmbed> embed = default)
```

### Parameters

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New content.

`embed` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

New embed.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmbed___"></a>ModifyAsync\(Optional<string\>, Optional<IEnumerable<DiscordEmbed\>\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Optional<string> content, Optional<IEnumerable<DiscordEmbed>> embeds = default)
```

### Parameters

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New content.

`embeds` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>\>

New embeds.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_DSharpPlus_Entities_DiscordMessageBuilder_System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>ModifyAsync\(DiscordMessageBuilder, bool, IEnumerable<DiscordAttachment\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordMessageBuilder builder, bool suppressEmbeds = false, IEnumerable<DiscordAttachment> attachments = null)
```

### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The builder of the message to edit.

`suppressEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to suppress embeds on the message.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMessage_ModifyAsync_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>ModifyAsync\(Action<DiscordMessageBuilder\>, bool, IEnumerable<DiscordAttachment\>\)

Edits the message.

```csharp
public Task<DiscordMessage> ModifyAsync(Action<DiscordMessageBuilder> action, bool suppressEmbeds = false, IEnumerable<DiscordAttachment> attachments = null)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The builder of the message to edit.

`suppressEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to suppress embeds on the message.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client tried to modify a message not sent by them.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

