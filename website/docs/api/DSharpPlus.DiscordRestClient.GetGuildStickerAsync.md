# Method GetGuildStickerAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildStickerAsync_System_UInt64_System_UInt64_"></a>GetGuildStickerAsync\(ulong, ulong\)

Gets a sticker from a guild.

```csharp
public Task<DiscordMessageSticker> GetGuildStickerAsync(ulong guildId, ulong stickerId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

