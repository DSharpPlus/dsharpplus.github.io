# Method CreateWebhookAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_CreateWebhookAsync_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__System_String_"></a>CreateWebhookAsync\(string, Optional<Stream\>, string\)

Create a new webhook

```csharp
public Task<DiscordWebhook> CreateWebhookAsync(string name, Optional<Stream> avatar = default, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the webhook.

`avatar` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

The image for the default webhook avatar.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

