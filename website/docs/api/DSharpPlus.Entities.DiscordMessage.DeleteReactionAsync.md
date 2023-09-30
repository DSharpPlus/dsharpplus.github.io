# Method DeleteReactionAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessage_DeleteReactionAsync_DSharpPlus_Entities_DiscordEmoji_DSharpPlus_Entities_DiscordUser_System_String_"></a>DeleteReactionAsync\(DiscordEmoji, DiscordUser, string\)

Deletes another user's reaction.

```csharp
public Task DeleteReactionAsync(DiscordEmoji emoji, DiscordUser user, string reason = null)
```

### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji for the reaction you want to remove, either an emoji or name:id.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

Member you want to remove the reaction for

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

