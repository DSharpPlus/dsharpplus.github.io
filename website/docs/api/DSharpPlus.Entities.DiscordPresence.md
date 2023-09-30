# Class DiscordPresence

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a user presence.

```csharp
public sealed class DiscordPresence
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordPresence](DSharpPlus.Entities.DiscordPresence.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordPresence_Activities"></a>Activities

Gets the user's current activities.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordActivity> Activities { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)\>

### <a id="DSharpPlus_Entities_DiscordPresence_Activity"></a>Activity

Gets the user's current activity.

```csharp
[JsonIgnore]
public DiscordActivity Activity { get; }
```

#### Property Value

[DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)

### <a id="DSharpPlus_Entities_DiscordPresence_ClientStatus"></a>ClientStatus

Gets this user's platform-dependent status.

```csharp
[JsonProperty("client_status", NullValueHandling = NullValueHandling.Ignore)]
public DiscordClientStatus ClientStatus { get; }
```

#### Property Value

[DiscordClientStatus](DSharpPlus.Entities.DiscordClientStatus.md)

### <a id="DSharpPlus_Entities_DiscordPresence_Guild"></a>Guild

Gets the guild for which this presence was set.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordPresence_Status"></a>Status

Gets this user's status.

```csharp
[JsonProperty("status", NullValueHandling = NullValueHandling.Ignore)]
public UserStatus Status { get; }
```

#### Property Value

[UserStatus](DSharpPlus.Entities.UserStatus.md)

### <a id="DSharpPlus_Entities_DiscordPresence_User"></a>User

Gets the user that owns this presence.

```csharp
[JsonIgnore]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

