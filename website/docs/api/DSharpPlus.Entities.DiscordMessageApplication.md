# Class DiscordMessageApplication

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Rich Presence application.

```csharp
public class DiscordMessageApplication : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordMessageApplication](DSharpPlus.Entities.DiscordMessageApplication.md)

###### Derived

[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordMessageApplication_CoverImageUrl"></a>CoverImageUrl

Gets the ID of this application's cover image.

```csharp
[JsonProperty("cover_image")]
public virtual string CoverImageUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageApplication_Description"></a>Description

Gets the application's description.

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageApplication_Icon"></a>Icon

Gets the ID of the application's icon.

```csharp
[JsonProperty("icon")]
public virtual string Icon { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMessageApplication_Name"></a>Name

Gets the application's name.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

