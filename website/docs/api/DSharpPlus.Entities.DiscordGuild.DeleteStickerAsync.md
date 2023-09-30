# Method DeleteStickerAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_DeleteStickerAsync_System_UInt64_System_String_"></a>DeleteStickerAsync\(ulong, string\)

Deletes a sticker in this guild.

```csharp
public Task DeleteStickerAsync(ulong stickerId, string reason = null)
```

### Parameters

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_Entities_DiscordGuild_DeleteStickerAsync_DSharpPlus_Entities_DiscordMessageSticker_System_String_"></a>DeleteStickerAsync\(DiscordMessageSticker, string\)

Deletes a sticker in this guild.

```csharp
public Task DeleteStickerAsync(DiscordMessageSticker sticker, string reason = null)
```

### Parameters

`sticker` [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

Sticker to delete.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

