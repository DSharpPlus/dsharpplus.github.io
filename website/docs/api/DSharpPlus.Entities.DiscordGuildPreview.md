# Class DiscordGuildPreview

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a guild preview.

```csharp
public class DiscordGuildPreview : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordGuildPreview](DSharpPlus.Entities.DiscordGuildPreview.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildPreview_ApproximateMemberCount"></a>ApproximateMemberCount

Gets the approximate member count.

```csharp
[JsonProperty("approximate_member_count")]
public int ApproximateMemberCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordGuildPreview_ApproximatePresenceCount"></a>ApproximatePresenceCount

Gets the approximate presence count.

```csharp
[JsonProperty("approximate_presence_count")]
public int ApproximatePresenceCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordGuildPreview_Description"></a>Description

Gets the description for the guild, if the guild is discoverable.

```csharp
[JsonProperty("description", NullValueHandling = NullValueHandling.Ignore)]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildPreview_DiscoverySplash"></a>DiscoverySplash

Gets the guild's discovery splash.

```csharp
[JsonProperty("discovery_splash", NullValueHandling = NullValueHandling.Ignore)]
public string DiscoverySplash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildPreview_Emojis"></a>Emojis

Gets a collection of this guild's emojis.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordEmoji> Emojis { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

### <a id="DSharpPlus_Entities_DiscordGuildPreview_Features"></a>Features

Gets a collection of this guild's features.

```csharp
[JsonProperty("features", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<string> Features { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordGuildPreview_Icon"></a>Icon

Gets the guild's icon.

```csharp
[JsonProperty("icon", NullValueHandling = NullValueHandling.Ignore)]
public string Icon { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildPreview_Name"></a>Name

Gets the guild's name.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildPreview_Splash"></a>Splash

Gets the guild's splash.

```csharp
[JsonProperty("splash", NullValueHandling = NullValueHandling.Ignore)]
public string Splash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

