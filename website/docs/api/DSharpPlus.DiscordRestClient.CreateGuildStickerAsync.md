# Method CreateGuildStickerAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildStickerAsync_System_UInt64_System_String_System_String_System_String_System_IO_Stream_DSharpPlus_Entities_StickerFormat_System_String_"></a>CreateGuildStickerAsync\(ulong, string, string, string, Stream, StickerFormat, string\)

Creates a sticker in a guild.

```csharp
public Task<DiscordMessageSticker> CreateGuildStickerAsync(ulong guildId, string name, string description, string tags, Stream imageContents, StickerFormat format, string reason = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the sticker.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the sticker.

`tags` [string](https://learn.microsoft.com/dotnet/api/system.string)

The tags of the sticker.

`imageContents` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The image content of the sticker.

`format` [StickerFormat](DSharpPlus.Entities.StickerFormat.md)

The image format of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason this sticker is being created.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

