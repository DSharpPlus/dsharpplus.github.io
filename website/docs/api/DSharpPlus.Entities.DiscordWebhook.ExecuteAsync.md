# Method ExecuteAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordWebhook_ExecuteAsync_DSharpPlus_Entities_DiscordWebhookBuilder_"></a>ExecuteAsync\(DiscordWebhookBuilder\)

Executes this webhook with the given <xref href="DSharpPlus.Entities.DiscordWebhookBuilder" data-throw-if-not-resolved="false"></xref>.

```csharp
public Task<DiscordMessage> ExecuteAsync(DiscordWebhookBuilder builder)
```

### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

Webhook builder filled with data to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

