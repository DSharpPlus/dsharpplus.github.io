# Method TryFromUnicode

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordEmoji_TryFromUnicode_DSharpPlus_BaseDiscordClient_System_String_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromUnicode\(BaseDiscordClient, string, out DiscordEmoji\)

Attempts to create an emoji object from a unicode entity.

```csharp
public static bool TryFromUnicode(BaseDiscordClient client, string unicodeEntity, out DiscordEmoji emoji)
```

### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`unicodeEntity` [string](https://learn.microsoft.com/dotnet/api/system.string)

Unicode entity to create the object from.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

## <a id="DSharpPlus_Entities_DiscordEmoji_TryFromUnicode_System_String_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromUnicode\(string, out DiscordEmoji\)

Attempts to create an emoji object from a unicode entity.

```csharp
public static bool TryFromUnicode(string unicodeEntity, out DiscordEmoji emoji)
```

### Parameters

`unicodeEntity` [string](https://learn.microsoft.com/dotnet/api/system.string)

Unicode entity to create the object from.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

