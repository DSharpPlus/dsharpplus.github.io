# Method TryFromName

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordEmoji_TryFromName_DSharpPlus_BaseDiscordClient_System_String_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromName\(BaseDiscordClient, string, out DiscordEmoji\)

Attempts to create an emoji object from emote name that includes colons (eg. :thinking:). This method also
supports skin tone variations (eg. :ok_hand::skin-tone-2:), standard emoticons (eg. :D), as well as guild
emoji (still specified by :name:).

```csharp
public static bool TryFromName(BaseDiscordClient client, string name, out DiscordEmoji emoji)
```

### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emote to find, including colons (eg. :thinking:).

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

## <a id="DSharpPlus_Entities_DiscordEmoji_TryFromName_DSharpPlus_BaseDiscordClient_System_String_System_Boolean_DSharpPlus_Entities_DiscordEmoji__"></a>TryFromName\(BaseDiscordClient, string, bool, out DiscordEmoji\)

Attempts to create an emoji object from emote name that includes colons (eg. :thinking:). This method also
supports skin tone variations (eg. :ok_hand::skin-tone-2:), standard emoticons (eg. :D), as well as guild
emoji (still specified by :name:).

```csharp
public static bool TryFromName(BaseDiscordClient client, string name, bool includeGuilds, out DiscordEmoji emoji)
```

### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emote to find, including colons (eg. :thinking:).

`includeGuilds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Should guild emojis be included in the search.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Resulting <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation was successful.

