# Method ExecuteSlackAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordWebhook_ExecuteSlackAsync_System_String_"></a>ExecuteSlackAsync\(string\)

Executes this webhook in Slack compatibility mode.

```csharp
public Task ExecuteSlackAsync(string json)
```

### Parameters

`json` [string](https://learn.microsoft.com/dotnet/api/system.string)

JSON containing Slack-compatible payload for this webhook.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

