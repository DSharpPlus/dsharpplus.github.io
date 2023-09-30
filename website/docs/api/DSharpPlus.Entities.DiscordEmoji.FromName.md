# Method FromName

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordEmoji_FromName_DSharpPlus_BaseDiscordClient_System_String_System_Boolean_"></a>FromName\(BaseDiscordClient, string, bool\)

Creates an emoji object from emote name that includes colons (eg. :thinking:). This method also supports
skin tone variations (eg. :ok_hand::skin-tone-2:), standard emoticons (eg. :D), as well as guild emoji
(still specified by :name:).

```csharp
public static DiscordEmoji FromName(BaseDiscordClient client, string name, bool includeGuilds = true)
```

### Parameters

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

<xref href="DSharpPlus.BaseDiscordClient" data-throw-if-not-resolved="false"></xref> to attach to the object.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emote to find, including colons (eg. :thinking:).

`includeGuilds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Should guild emojis be included in the search.

### Returns

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Create <xref href="DSharpPlus.Entities.DiscordEmoji" data-throw-if-not-resolved="false"></xref> object.

