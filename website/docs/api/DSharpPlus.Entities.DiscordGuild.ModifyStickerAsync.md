# Method ModifyStickerAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyStickerAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_StickerEditModel__System_String_"></a>ModifyStickerAsync\(ulong, Action<StickerEditModel\>, string\)

Modifies a sticker in this guild.

```csharp
public Task<DiscordMessageSticker> ModifyStickerAsync(ulong stickerId, Action<StickerEditModel> action, string reason = null)
```

### Parameters

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the sticker.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StickerEditModel](DSharpPlus.Net.Models.StickerEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyStickerAsync_DSharpPlus_Entities_DiscordMessageSticker_System_Action_DSharpPlus_Net_Models_StickerEditModel__System_String_"></a>ModifyStickerAsync\(DiscordMessageSticker, Action<StickerEditModel\>, string\)

Modifies a sticker in this guild.

```csharp
public Task<DiscordMessageSticker> ModifyStickerAsync(DiscordMessageSticker sticker, Action<StickerEditModel> action, string reason = null)
```

### Parameters

`sticker` [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

Sticker to modify.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StickerEditModel](DSharpPlus.Net.Models.StickerEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

