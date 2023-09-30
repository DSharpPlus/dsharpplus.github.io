# Class DiscordEmbedThumbnail

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a thumbnail in an embed.

```csharp
public sealed class DiscordEmbedThumbnail
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedThumbnail](DSharpPlus.Entities.DiscordEmbedThumbnail.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedThumbnail_Height"></a>Height

Gets the height of the thumbnail.

```csharp
[JsonProperty("height", NullValueHandling = NullValueHandling.Ignore)]
public int Height { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordEmbedThumbnail_ProxyUrl"></a>ProxyUrl

Gets a proxied url of the thumbnail.

```csharp
[JsonProperty("proxy_url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri ProxyUrl { get; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedThumbnail_Url"></a>Url

Gets the source url of the thumbnail (only https).

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri Url { get; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedThumbnail_Width"></a>Width

Gets the width of the thumbnail.

```csharp
[JsonProperty("width", NullValueHandling = NullValueHandling.Ignore)]
public int Width { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

