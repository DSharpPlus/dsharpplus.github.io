# Method DeleteGuildStickerAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteGuildStickerAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteGuildStickerAsync\(ulong, ulong, string\)

Deletes a sticker in a guild.

```csharp
public Task DeleteGuildStickerAsync(ulong guildId, ulong stickerId, string reason = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

