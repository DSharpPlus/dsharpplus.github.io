# Method CreateEmojiAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateEmojiAsync_System_UInt64_System_String_System_IO_Stream_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>CreateEmojiAsync\(ulong, string, Stream, IEnumerable<ulong\>, string\)

Creates an emoji in a guild.

```csharp
public Task<DiscordGuildEmoji> CreateEmojiAsync(ulong guildId, string name, Stream image, IEnumerable<ulong> roles = null, string reason = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emoji.

`image` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Image to use as the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Roles for which the emoji will be available.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

