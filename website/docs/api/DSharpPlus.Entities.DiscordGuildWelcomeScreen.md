# Class DiscordGuildWelcomeScreen

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a discord welcome screen object.

```csharp
public class DiscordGuildWelcomeScreen
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildWelcomeScreen_Description"></a>Description

Gets the server description shown in the welcome screen.

```csharp
[JsonProperty("description", NullValueHandling = NullValueHandling.Ignore)]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuildWelcomeScreen_WelcomeChannels"></a>WelcomeChannels

Gets the channels shown in the welcome screen.

```csharp
[JsonProperty("welcome_channels", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<DiscordGuildWelcomeScreenChannel> WelcomeChannels { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildWelcomeScreenChannel](DSharpPlus.Entities.DiscordGuildWelcomeScreenChannel.md)\>

