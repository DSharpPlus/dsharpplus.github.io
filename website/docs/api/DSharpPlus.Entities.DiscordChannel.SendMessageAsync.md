# Method SendMessageAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_System_String_"></a>SendMessageAsync\(string\)

Sends a message to this channel.

```csharp
public Task<DiscordMessage> SendMessageAsync(string content)
```

### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content of the message to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordEmbed\)

Sends a message to this channel.

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordEmbed embed)
```

### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(string, DiscordEmbed\)

Sends a message to this channel.

```csharp
public Task<DiscordMessage> SendMessageAsync(string content, DiscordEmbed embed)
```

### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content of the message to send.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_DSharpPlus_Entities_DiscordMessageBuilder_"></a>SendMessageAsync\(DiscordMessageBuilder\)

Sends a message to this channel.

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordMessageBuilder builder)
```

### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The builder with all the items to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>SendMessageAsync\(Action<DiscordMessageBuilder\>\)

Sends a message to this channel.

```csharp
public Task<DiscordMessage> SendMessageAsync(Action<DiscordMessageBuilder> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The builder with all the items to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

