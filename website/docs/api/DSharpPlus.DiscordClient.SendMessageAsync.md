# Method SendMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_System_String_"></a>SendMessageAsync\(DiscordChannel, string\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, string content)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message content to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordChannel, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, DiscordEmbed embed)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordChannel, string, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, string content, DiscordEmbed embed)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message content to send.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordMessageBuilder_"></a>SendMessageAsync\(DiscordChannel, DiscordMessageBuilder\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, DiscordMessageBuilder builder)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The Discord Message builder.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is false and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>SendMessageAsync\(DiscordChannel, Action<DiscordMessageBuilder\>\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, Action<DiscordMessageBuilder> action)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The Discord Message builder.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is false and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

