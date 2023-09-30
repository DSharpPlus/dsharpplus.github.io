# Class DiscordAsset

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public abstract class DiscordAsset
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordAsset](DSharpPlus.Entities.DiscordAsset.md)

###### Derived

[DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md), 
[DiscordSpotifyAsset](DSharpPlus.Entities.DiscordSpotifyAsset.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordAsset_Id"></a>Id

Gets the ID of this asset.

```csharp
public virtual string Id { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordAsset_Url"></a>Url

Gets the URL of this asset.

```csharp
public abstract Uri Url { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

