# Method GetWebhookWithTokenAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetWebhookWithTokenAsync_System_UInt64_System_String_"></a>GetWebhookWithTokenAsync\(ulong, string\)

Gets a webhook

```csharp
public Task<DiscordWebhook> GetWebhookWithTokenAsync(ulong id, string token)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of webhook to get.

`token` [string](https://learn.microsoft.com/dotnet/api/system.string)

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

