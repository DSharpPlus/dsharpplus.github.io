# Method DeleteOwnReactionAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessage_DeleteOwnReactionAsync_DSharpPlus_Entities_DiscordEmoji_"></a>DeleteOwnReactionAsync\(DiscordEmoji\)

Deletes your own reaction

```csharp
public Task DeleteOwnReactionAsync(DiscordEmoji emoji)
```

### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji for the reaction you want to remove, either an emoji or name:id

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

