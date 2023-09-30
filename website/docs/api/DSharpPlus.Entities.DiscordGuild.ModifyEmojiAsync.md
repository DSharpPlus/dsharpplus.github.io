# Method ModifyEmojiAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyEmojiAsync_DSharpPlus_Entities_DiscordGuildEmoji_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>ModifyEmojiAsync\(DiscordGuildEmoji, string, IEnumerable<DiscordRole\>, string\)

Modifies a this guild's custom emoji.

```csharp
public Task<DiscordGuildEmoji> ModifyEmojiAsync(DiscordGuildEmoji emoji, string name, IEnumerable<DiscordRole> roles = null, string reason = null)
```

### Parameters

`emoji` [DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)

Emoji to modify.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New name for the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

Roles for which the emoji will be available. This works only if your application is whitelisted as integration.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

The modified emoji.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

