# Class DiscordEmbedVideo

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a video inside an embed.

```csharp
public sealed class DiscordEmbedVideo
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedVideo](DSharpPlus.Entities.DiscordEmbedVideo.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedVideo_Height"></a>Height

Gets the height of the video.

```csharp
[JsonProperty("height", NullValueHandling = NullValueHandling.Ignore)]
public int Height { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordEmbedVideo_Url"></a>Url

Gets the source url of the video.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public Uri Url { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

### <a id="DSharpPlus_Entities_DiscordEmbedVideo_Width"></a>Width

Gets the width of the video.

```csharp
[JsonProperty("width", NullValueHandling = NullValueHandling.Ignore)]
public int Width { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

