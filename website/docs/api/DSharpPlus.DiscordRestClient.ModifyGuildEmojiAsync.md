# Method ModifyGuildEmojiAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildEmojiAsync_System_UInt64_System_UInt64_System_String_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>ModifyGuildEmojiAsync\(ulong, ulong, string, IEnumerable<ulong\>, string\)

Modifies a guild's emoji.

```csharp
public Task<DiscordGuildEmoji> ModifyGuildEmojiAsync(ulong guildId, ulong emojiId, string name, IEnumerable<ulong> roles = null, string reason = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`emojiId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the emoji.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New name of the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Roles for which the emoji will be available.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

