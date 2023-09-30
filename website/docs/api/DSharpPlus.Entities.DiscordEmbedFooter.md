# Class DiscordEmbedFooter

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a footer in an embed.

```csharp
public sealed class DiscordEmbedFooter
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedFooter](DSharpPlus.Entities.DiscordEmbedFooter.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedFooter_IconUrl"></a>IconUrl

Gets the url of the footer's icon.

```csharp
[JsonProperty("icon_url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri IconUrl { get; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedFooter_ProxyIconUrl"></a>ProxyIconUrl

Gets the proxied url of the footer's icon.

```csharp
[JsonProperty("proxy_icon_url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri ProxyIconUrl { get; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedFooter_Text"></a>Text

Gets the footer's text.

```csharp
[JsonProperty("text", NullValueHandling = NullValueHandling.Ignore)]
public string Text { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

