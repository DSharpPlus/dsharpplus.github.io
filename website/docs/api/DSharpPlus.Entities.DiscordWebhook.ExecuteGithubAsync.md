# Method ExecuteGithubAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordWebhook_ExecuteGithubAsync_System_String_"></a>ExecuteGithubAsync\(string\)

Executes this webhook in GitHub compatibility mode.

```csharp
public Task ExecuteGithubAsync(string json)
```

### Parameters

`json` [string](https://learn.microsoft.com/dotnet/api/system.string)

JSON containing GitHub-compatible payload for this webhook.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

