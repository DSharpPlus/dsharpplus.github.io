# Method SendMessageAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_System_String_"></a>SendMessageAsync\(string\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

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

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordEmbed\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

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

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(string, DiscordEmbed\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

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

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_DSharpPlus_Entities_DiscordMessageBuilder_"></a>SendMessageAsync\(DiscordMessageBuilder\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordMessageBuilder message)
```

### Parameters

`message` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

Builder to with the message.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

