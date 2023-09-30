# Class DiscordEmbedAuthor

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Gets the author of a discord embed.

```csharp
public sealed class DiscordEmbedAuthor
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedAuthor](DSharpPlus.Entities.DiscordEmbedAuthor.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedAuthor_IconUrl"></a>IconUrl

Gets the url of the author's icon.

```csharp
[JsonProperty("icon_url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri IconUrl { get; set; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedAuthor_Name"></a>Name

Gets the name of the author.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbedAuthor_ProxyIconUrl"></a>ProxyIconUrl

Gets the proxied url of the author's icon.

```csharp
[JsonProperty("proxy_icon_url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri ProxyIconUrl { get; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedAuthor_Url"></a>Url

Gets the url of the author.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public Uri Url { get; set; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

