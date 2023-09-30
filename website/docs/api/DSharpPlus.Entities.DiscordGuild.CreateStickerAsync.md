# Method CreateStickerAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateStickerAsync_System_String_System_String_System_String_System_IO_Stream_DSharpPlus_Entities_StickerFormat_System_String_"></a>CreateStickerAsync\(string, string, string, Stream, StickerFormat, string\)

Creates a sticker in this guild. Lottie stickers can only be created on verified and/or partnered servers.

```csharp
public Task<DiscordMessageSticker> CreateStickerAsync(string name, string description, string tags, Stream imageContents, StickerFormat format, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the sticker.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the sticker.

`tags` [string](https://learn.microsoft.com/dotnet/api/system.string)

The tags of the sticker. This must be a unicode emoji.

`imageContents` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The image content of the sticker.

`format` [StickerFormat](DSharpPlus.Entities.StickerFormat.md)

The image format of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason this sticker is being created.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

