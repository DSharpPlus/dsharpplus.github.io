# Method ModifyGuildStickerAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildStickerAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_StickerEditModel__System_String_"></a>ModifyGuildStickerAsync\(ulong, ulong, Action<StickerEditModel\>, string\)

Modifies a sticker in a guild.

```csharp
public Task<DiscordMessageSticker> ModifyGuildStickerAsync(ulong guildId, ulong stickerId, Action<StickerEditModel> action, string reason = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StickerEditModel](DSharpPlus.Net.Models.StickerEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

