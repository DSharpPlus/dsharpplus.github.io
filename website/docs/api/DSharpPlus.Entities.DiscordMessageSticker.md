# Class DiscordMessageSticker

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord Sticker.

```csharp
public class DiscordMessageSticker : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Asset"></a>Asset

Gets the asset hash of the sticker.

```csharp
[JsonProperty("asset")]
public string Asset { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Available"></a>Available

Gets whether this sticker is available. Only applicable to guild stickers.

```csharp
[JsonProperty("available")]
public bool Available { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_BannerUrl"></a>BannerUrl

```csharp
public string BannerUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Description"></a>Description

Gets the Description of the sticker.

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_FormatType"></a>FormatType

Gets the Format type of the sticker.

```csharp
[JsonProperty("format_type")]
public StickerFormat FormatType { get; }
```

#### Property Value

[StickerFormat](DSharpPlus.Entities.StickerFormat.md)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Guild"></a>Guild

Gets the guild associated with this sticker, if any.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_GuildId"></a>GuildId

Gets the Id of the sticker this guild belongs to, if any.

```csharp
[JsonProperty("guild_id")]
public ulong? GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Name"></a>Name

Gets the Name of the sticker.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_PackId"></a>PackId

Gets the Pack ID of this sticker.

```csharp
[JsonProperty("pack_id")]
public ulong PackId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_PreviewAsset"></a>PreviewAsset

Gets the preview asset hash of the sticker.

```csharp
[JsonProperty("preview_asset", NullValueHandling = NullValueHandling.Ignore)]
public string PreviewAsset { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_SortValue"></a>SortValue

Gets the sticker's sort order, if it's in a pack.

```csharp
[JsonProperty("sort_value")]
public int SortValue { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_StickerUrl"></a>StickerUrl

```csharp
public string StickerUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Tags"></a>Tags

Gets the list of tags for the sticker.

```csharp
[JsonIgnore]
public IReadOnlyList<string> Tags { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Type"></a>Type

Gets the type of sticker.

```csharp
[JsonProperty("type")]
public StickerType Type { get; }
```

#### Property Value

[StickerType](DSharpPlus.Entities.StickerType.md)

### <a id="DSharpPlus_Entities_DiscordMessageSticker_User"></a>User

For guild stickers, gets the user that made the sticker.

```csharp
[JsonProperty("user")]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordMessageSticker_Equals_DSharpPlus_Entities_DiscordMessageSticker_"></a>Equals\(DiscordMessageSticker\)

Indicates whether the current object is equal to another object of the same type.

```csharp
public bool Equals(DiscordMessageSticker other)
```

#### Parameters

`other` [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

An object to compare with this object.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if the current object is equal to the <code class="paramref">other</code> parameter; otherwise, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">false</a>.

### <a id="DSharpPlus_Entities_DiscordMessageSticker_ToString"></a>ToString\(\)

Returns a string that represents the current object.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string that represents the current object.

