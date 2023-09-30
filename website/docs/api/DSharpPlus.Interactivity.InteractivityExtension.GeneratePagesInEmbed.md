# Method GeneratePagesInEmbed

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_GeneratePagesInEmbed_System_String_DSharpPlus_Interactivity_Enums_SplitType_DSharpPlus_Entities_DiscordEmbedBuilder_"></a>GeneratePagesInEmbed\(string, SplitType, DiscordEmbedBuilder\)

Generates pages from a string, and puts them in message embeds.

```csharp
public IEnumerable<Page> GeneratePagesInEmbed(string input, SplitType splittype = SplitType.Character, DiscordEmbedBuilder embedbase = null)
```

### Parameters

`input` [string](https://learn.microsoft.com/dotnet/api/system.string)

Input string.

`splittype` [SplitType](DSharpPlus.Interactivity.Enums.SplitType.md)

How to split input string.

`embedbase` [DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

Base embed for output embeds.

### Returns

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

