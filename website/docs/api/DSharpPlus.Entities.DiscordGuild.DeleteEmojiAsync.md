# Method DeleteEmojiAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_DeleteEmojiAsync_DSharpPlus_Entities_DiscordGuildEmoji_System_String_"></a>DeleteEmojiAsync\(DiscordGuildEmoji, string?\)

Deletes this guild's custom emoji.

```csharp
public Task DeleteEmojiAsync(DiscordGuildEmoji emoji, string? reason = null)
```

### Parameters

`emoji` [DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)

Emoji to delete.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

