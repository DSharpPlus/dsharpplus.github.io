# Method GetMessageAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordWebhook_GetMessageAsync_System_UInt64_"></a>GetMessageAsync\(ulong\)

Gets a previously-sent webhook message.

```csharp
public Task<DiscordMessage> GetMessageAsync(ulong messageId)
```

### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook or message does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

