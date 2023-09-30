# Method CreateThreadAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessage_CreateThreadAsync_System_String_DSharpPlus_AutoArchiveDuration_System_String_"></a>CreateThreadAsync\(string, AutoArchiveDuration, string\)

Creates a new thread within this channel from this message.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(string name, AutoArchiveDuration archiveAfter, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration of the thread. Three and seven day archive options are locked behind level 2 and level 3 server boosts respectively.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

The created thread.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

