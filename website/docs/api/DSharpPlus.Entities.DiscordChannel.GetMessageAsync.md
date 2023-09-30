# Method GetMessageAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_GetMessageAsync_System_UInt64_System_Boolean_"></a>GetMessageAsync\(ulong, bool\)

Returns a specific message

```csharp
public Task<DiscordMessage> GetMessageAsync(ulong id, bool skipCache = false)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message

`skipCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Remarks

Cached message objects will not be returned if <xref href="DSharpPlus.DiscordConfiguration.MessageCacheSize" data-throw-if-not-resolved="false"></xref> is set to zero, if the client does not have the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordIntents.DirectMessages" data-throw-if-not-resolved="false"></xref> intents, or if the discord client is a <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ReadMessageHistory" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

