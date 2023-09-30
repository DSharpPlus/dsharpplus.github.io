# Method TryFromGuildEmote

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordEmoji_TryFromGuildEmote_DSharpPlus_BaseDiscordClient_System_UInt64_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromGuildEmote\(BaseDiscordClient, ulong, out DiscordEmoji\)

Attempts to create an emoji object from a guild emote.

```csharp
public static bool TryFromGuildEmote(BaseDiscordClient client, ulong id, out DiscordEmoji emoji)
```

### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Id of the emote.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

