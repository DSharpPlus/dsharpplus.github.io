# Method CreateEmojiAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateEmojiAsync_System_String_System_IO_Stream_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>CreateEmojiAsync\(string, Stream, IEnumerable<DiscordRole\>, string\)

Creates a new custom emoji for this guild.

```csharp
public Task<DiscordGuildEmoji> CreateEmojiAsync(string name, Stream image, IEnumerable<DiscordRole> roles = null, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the new emoji.

`image` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Image to use as the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

Roles for which the emoji will be available. This works only if your application is whitelisted as integration.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

The newly-created emoji.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

