# Method GetMessagesAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_GetMessagesAsync_System_Int32_"></a>GetMessagesAsync\(int\)

Returns a list of messages from the last message in the channel.
<param name="limit">The amount of messages to fetch.</param>

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetMessagesAsync(int limit = 100)
```

### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AccessChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

