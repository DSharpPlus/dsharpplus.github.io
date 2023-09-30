# Class DiscordClientStatus

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordClientStatus
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordClientStatus](DSharpPlus.Entities.DiscordClientStatus.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordClientStatus_Desktop"></a>Desktop

Gets the user's status set for an active desktop (Windows, Linux, Mac) application session.

```csharp
[JsonProperty("desktop", NullValueHandling = NullValueHandling.Ignore)]
public Optional<UserStatus> Desktop { get; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[UserStatus](DSharpPlus.Entities.UserStatus.md)\>

### <a id="DSharpPlus_Entities_DiscordClientStatus_Mobile"></a>Mobile

Gets the user's status set for an active mobile (iOS, Android) application session.

```csharp
[JsonProperty("mobile", NullValueHandling = NullValueHandling.Ignore)]
public Optional<UserStatus> Mobile { get; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[UserStatus](DSharpPlus.Entities.UserStatus.md)\>

### <a id="DSharpPlus_Entities_DiscordClientStatus_Web"></a>Web

Gets the user's status set for an active web (browser, bot account) application session.

```csharp
[JsonProperty("web", NullValueHandling = NullValueHandling.Ignore)]
public Optional<UserStatus> Web { get; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[UserStatus](DSharpPlus.Entities.UserStatus.md)\>

