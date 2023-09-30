# Method DeleteGuildEmojiAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteGuildEmojiAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteGuildEmojiAsync\(ulong, ulong, string\)

Deletes a guild's emoji.

```csharp
public Task DeleteGuildEmojiAsync(ulong guildId, ulong emojiId, string reason = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`emojiId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the emoji.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

