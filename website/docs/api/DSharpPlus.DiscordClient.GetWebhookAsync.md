# Method GetWebhookAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetWebhookAsync_System_UInt64_"></a>GetWebhookAsync\(ulong\)

Gets a webhook

```csharp
public Task<DiscordWebhook> GetWebhookAsync(ulong id)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of webhook to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

