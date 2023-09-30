# Class DiscordEmbed

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a discord embed.

```csharp
public sealed class DiscordEmbed
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbed_Author"></a>Author

Gets the embed's author.

```csharp
[JsonProperty("author", NullValueHandling = NullValueHandling.Ignore)]
public DiscordEmbedAuthor Author { get; }
```

#### Property Value

[DiscordEmbedAuthor](DSharpPlus.Entities.DiscordEmbedAuthor.md)

### <a id="DSharpPlus_Entities_DiscordEmbed_Color"></a>Color

Gets the embed's color.

```csharp
[JsonIgnore]
public Optional<DiscordColor> Color { get; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordColor](DSharpPlus.Entities.DiscordColor.md)\>

### <a id="DSharpPlus_Entities_DiscordEmbed_Description"></a>Description

Gets the embed's description.

```csharp
[JsonProperty("description", NullValueHandling = NullValueHandling.Ignore)]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbed_Fields"></a>Fields

Gets the embed's fields.

```csharp
[JsonProperty("fields", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<DiscordEmbedField> Fields { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordEmbedField](DSharpPlus.Entities.DiscordEmbedField.md)\>

### <a id="DSharpPlus_Entities_DiscordEmbed_Footer"></a>Footer

Gets the embed's footer.

```csharp
[JsonProperty("footer", NullValueHandling = NullValueHandling.Ignore)]
public DiscordEmbedFooter Footer { get; }
```

#### Property Value

[DiscordEmbedFooter](DSharpPlus.Entities.DiscordEmbedFooter.md)

### <a id="DSharpPlus_Entities_DiscordEmbed_Image"></a>Image

Gets the embed's image.

```csharp
[JsonProperty("image", NullValueHandling = NullValueHandling.Ignore)]
public DiscordEmbedImage Image { get; }
```

#### Property Value

[DiscordEmbedImage](DSharpPlus.Entities.DiscordEmbedImage.md)

### <a id="DSharpPlus_Entities_DiscordEmbed_Provider"></a>Provider

Gets the embed's provider.

```csharp
[JsonProperty("provider", NullValueHandling = NullValueHandling.Ignore)]
public DiscordEmbedProvider Provider { get; }
```

#### Property Value

[DiscordEmbedProvider](DSharpPlus.Entities.DiscordEmbedProvider.md)

### <a id="DSharpPlus_Entities_DiscordEmbed_Thumbnail"></a>Thumbnail

Gets the embed's thumbnail.

```csharp
[JsonProperty("thumbnail", NullValueHandling = NullValueHandling.Ignore)]
public DiscordEmbedThumbnail Thumbnail { get; }
```

#### Property Value

[DiscordEmbedThumbnail](DSharpPlus.Entities.DiscordEmbedThumbnail.md)

### <a id="DSharpPlus_Entities_DiscordEmbed_Timestamp"></a>Timestamp

Gets the embed's timestamp.

```csharp
[JsonProperty("timestamp", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? Timestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordEmbed_Title"></a>Title

Gets the embed's title.

```csharp
[JsonProperty("title", NullValueHandling = NullValueHandling.Ignore)]
public string Title { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbed_Type"></a>Type

Gets the embed's type.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public string Type { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbed_Url"></a>Url

Gets the embed's url.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public Uri Url { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

### <a id="DSharpPlus_Entities_DiscordEmbed_Video"></a>Video

Gets the embed's video.

```csharp
[JsonProperty("video", NullValueHandling = NullValueHandling.Ignore)]
public DiscordEmbedVideo Video { get; }
```

#### Property Value

[DiscordEmbedVideo](DSharpPlus.Entities.DiscordEmbedVideo.md)

