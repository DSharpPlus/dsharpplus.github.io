# Class DiscordAttachment

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an attachment for a message.

```csharp
public class DiscordAttachment : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordAttachment_Ephemeral"></a>Ephemeral

Gets whether this attachment is ephemeral.

```csharp
[JsonProperty("ephemeral", NullValueHandling = NullValueHandling.Ignore)]
public bool? Ephemeral { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordAttachment_FileName"></a>FileName

Gets the name of the file.

```csharp
[JsonProperty("filename", NullValueHandling = NullValueHandling.Ignore)]
public string FileName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordAttachment_FileSize"></a>FileSize

Gets the file size in bytes.

```csharp
[JsonProperty("size", NullValueHandling = NullValueHandling.Ignore)]
public int FileSize { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordAttachment_Height"></a>Height

Gets the height. Applicable only if the attachment is an image.

```csharp
[JsonProperty("height", NullValueHandling = NullValueHandling.Ignore)]
public int? Height { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordAttachment_MediaType"></a>MediaType

Gets the media, or MIME, type of the file.

```csharp
[JsonProperty("content_type", NullValueHandling = NullValueHandling.Ignore)]
public string MediaType { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordAttachment_ProxyUrl"></a>ProxyUrl

Gets the proxied URL of the file.

```csharp
[JsonProperty("proxy_url", NullValueHandling = NullValueHandling.Ignore)]
public string ProxyUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordAttachment_Url"></a>Url

Gets the URL of the file.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public string Url { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordAttachment_Width"></a>Width

Gets the width. Applicable only if the attachment is an image.

```csharp
[JsonProperty("width", NullValueHandling = NullValueHandling.Ignore)]
public int? Width { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

