# Class DiscordInviteGuild

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a guild to which the user is invited.

```csharp
public class DiscordInviteGuild : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordInviteGuild](DSharpPlus.Entities.DiscordInviteGuild.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordInviteGuild_Banner"></a>Banner

Gets the guild's banner hash, when applicable.

```csharp
[JsonProperty("banner", NullValueHandling = NullValueHandling.Ignore)]
public string Banner { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_BannerUrl"></a>BannerUrl

Gets the guild's banner in url form.

```csharp
[JsonIgnore]
public string BannerUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_Description"></a>Description

Gets the guild description, when applicable.

```csharp
[JsonProperty("description", NullValueHandling = NullValueHandling.Ignore)]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_Features"></a>Features

Gets a collection of this guild's features.

```csharp
[JsonProperty("features", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<string> Features { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordInviteGuild_IconHash"></a>IconHash

Gets the guild icon's hash.

```csharp
[JsonProperty("icon", NullValueHandling = NullValueHandling.Ignore)]
public string IconHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_IconUrl"></a>IconUrl

Gets the guild icon's url.

```csharp
[JsonIgnore]
public string IconUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_Name"></a>Name

Gets the name of the guild.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_SplashUrl"></a>SplashUrl

Gets the URL of guild's invite splash.

```csharp
[JsonIgnore]
public string SplashUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_VanityUrlCode"></a>VanityUrlCode

Gets vanity URL code for this guild, when applicable.

```csharp
[JsonProperty("vanity_url_code")]
public string VanityUrlCode { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_VerificationLevel"></a>VerificationLevel

Gets the guild's verification level.

```csharp
[JsonProperty("verification_level", NullValueHandling = NullValueHandling.Ignore)]
public VerificationLevel VerificationLevel { get; }
```

#### Property Value

[VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)

### <a id="DSharpPlus_Entities_DiscordInviteGuild_WelcomeScreen"></a>WelcomeScreen

Gets the guild's welcome screen, when applicable.

```csharp
[JsonProperty("welcome_screen", NullValueHandling = NullValueHandling.Ignore)]
public DiscordGuildWelcomeScreen WelcomeScreen { get; }
```

#### Property Value

[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)

