# Class DiscordEmbedImage

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an image in an embed.

```csharp
public sealed class DiscordEmbedImage
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedImage](DSharpPlus.Entities.DiscordEmbedImage.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedImage_Height"></a>Height

Gets the height of the image.

```csharp
[JsonProperty("height", NullValueHandling = NullValueHandling.Ignore)]
public int Height { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordEmbedImage_ProxyUrl"></a>ProxyUrl

Gets a proxied url of the image.

```csharp
[JsonProperty("proxy_url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri ProxyUrl { get; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedImage_Url"></a>Url

Gets the source url of the image.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUri Url { get; }
```

#### Property Value

[DiscordUri](DSharpPlus.Net.DiscordUri.md)

### <a id="DSharpPlus_Entities_DiscordEmbedImage_Width"></a>Width

Gets the width of the image.

```csharp
[JsonProperty("width", NullValueHandling = NullValueHandling.Ignore)]
public int Width { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

