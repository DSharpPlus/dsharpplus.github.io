# Class DiscordMessageStickerPack

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord message sticker pack.

```csharp
public sealed class DiscordMessageStickerPack : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordMessageStickerPack](DSharpPlus.Entities.DiscordMessageStickerPack.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordMessageStickerPack_BannerAssetId"></a>BannerAssetId

Gets the Id of the sticker pack's banner image.

```csharp
[JsonProperty("banner_asset_id")]
public ulong BannerAssetId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordMessageStickerPack_CoverStickerId"></a>CoverStickerId

Gets the Id of this pack's cover.

```csharp
[JsonProperty("cover_sticker_id")]
public ulong CoverStickerId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordMessageStickerPack_Description"></a>Description

Gets the description of this sticker pack.

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageStickerPack_Name"></a>Name

Gets the name of this sticker pack.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageStickerPack_SkuId"></a>SkuId

Gets the Id of this pack's SKU.

```csharp
[JsonProperty("sku_id")]
public ulong SkuId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordMessageStickerPack_Stickers"></a>Stickers

Gets the stickers contained in this pack.

```csharp
public IReadOnlyDictionary<ulong, DiscordMessageSticker> Stickers { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

