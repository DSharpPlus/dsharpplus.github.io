# Method DeleteMessageAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordWebhook_DeleteMessageAsync_System_UInt64_"></a>DeleteMessageAsync\(ulong\)

Deletes a message that was created by the webhook.

```csharp
public Task DeleteMessageAsync(ulong messageId)
```

### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the message to delete

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

