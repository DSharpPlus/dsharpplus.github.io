# Method CreateDmChannelAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMember_CreateDmChannelAsync"></a>CreateDmChannelAsync\(\)

Creates a direct message channel to this member.

```csharp
public Task<DiscordDmChannel> CreateDmChannelAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

Direct message channel to this member.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

