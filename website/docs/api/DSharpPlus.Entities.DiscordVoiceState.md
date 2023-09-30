# Class DiscordVoiceState

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord voice state.

```csharp
public class DiscordVoiceState
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordVoiceState](DSharpPlus.Entities.DiscordVoiceState.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordVoiceState_Channel"></a>Channel

Gets the channel this user is connected to.

```csharp
[JsonIgnore]
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordVoiceState_Guild"></a>Guild

Gets the guild associated with this voice state.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordVoiceState_IsSelfDeafened"></a>IsSelfDeafened

Gets whether this user is locally deafened.

```csharp
[JsonProperty("self_deaf", NullValueHandling = NullValueHandling.Ignore)]
public bool IsSelfDeafened { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceState_IsSelfMuted"></a>IsSelfMuted

Gets whether this user is locally muted.

```csharp
[JsonProperty("self_mute", NullValueHandling = NullValueHandling.Ignore)]
public bool IsSelfMuted { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceState_IsSelfStream"></a>IsSelfStream

Gets whether this user is using the Go Live feature.

```csharp
[JsonProperty("self_stream", NullValueHandling = NullValueHandling.Ignore)]
public bool IsSelfStream { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceState_IsSelfVideo"></a>IsSelfVideo

Gets whether this user's camera is enabled.

```csharp
[JsonProperty("self_video", NullValueHandling = NullValueHandling.Ignore)]
public bool IsSelfVideo { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceState_IsServerDeafened"></a>IsServerDeafened

Gets whether this user is deafened.

```csharp
[JsonProperty("deaf", NullValueHandling = NullValueHandling.Ignore)]
public bool IsServerDeafened { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceState_IsServerMuted"></a>IsServerMuted

Gets whether this user is muted.

```csharp
[JsonProperty("mute", NullValueHandling = NullValueHandling.Ignore)]
public bool IsServerMuted { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceState_IsSuppressed"></a>IsSuppressed

Gets whether the current user has suppressed this user.

```csharp
[JsonProperty("suppress", NullValueHandling = NullValueHandling.Ignore)]
public bool IsSuppressed { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordVoiceState_Member"></a>Member

Gets the member this voice state belongs to.

```csharp
[JsonIgnore]
public DiscordMember Member { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_Entities_DiscordVoiceState_User"></a>User

Gets the user associated with this voice state.
<p>This can be cast to a <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> if this voice state was in a guild.</p>

```csharp
[JsonIgnore]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordVoiceState_ToString"></a>ToString\(\)

Returns a string that represents the current object.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A string that represents the current object.

