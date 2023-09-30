# Class DiscordRichPresence

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents details for Discord rich presence, attached to a <xref href="DSharpPlus.Entities.DiscordActivity" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordRichPresence
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordRichPresence](DSharpPlus.Entities.DiscordRichPresence.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordRichPresence_Application"></a>Application

Gets the application for which the rich presence is for.

```csharp
public DiscordApplication Application { get; }
```

#### Property Value

[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

### <a id="DSharpPlus_Entities_DiscordRichPresence_Buttons"></a>Buttons

Gets the buttons for the rich presence.

```csharp
public IReadOnlyList<string> Buttons { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordRichPresence_CurrentPartySize"></a>CurrentPartySize

Gets the current party size.

```csharp
public long? CurrentPartySize { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)?

### <a id="DSharpPlus_Entities_DiscordRichPresence_Details"></a>Details

Gets the details of this presence.

```csharp
public string Details { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRichPresence_EndTimestamp"></a>EndTimestamp

Gets the game end timestamp.

```csharp
public DateTimeOffset? EndTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordRichPresence_Instance"></a>Instance

Gets the instance status.

```csharp
public bool? Instance { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordRichPresence_JoinSecret"></a>JoinSecret

Gets the secret value enabling users to join your game.

```csharp
public string JoinSecret { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRichPresence_LargeImage"></a>LargeImage

Gets the large image for the rich presence.

```csharp
public DiscordAsset LargeImage { get; }
```

#### Property Value

[DiscordAsset](DSharpPlus.Entities.DiscordAsset.md)

### <a id="DSharpPlus_Entities_DiscordRichPresence_LargeImageText"></a>LargeImageText

Gets the hovertext for large image.

```csharp
public string LargeImageText { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRichPresence_MatchSecret"></a>MatchSecret

Gets the secret value enabling users to receive notifications whenever your game state changes.

```csharp
public string MatchSecret { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRichPresence_MaximumPartySize"></a>MaximumPartySize

Gets the maximum party size.

```csharp
public long? MaximumPartySize { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)?

### <a id="DSharpPlus_Entities_DiscordRichPresence_PartyId"></a>PartyId

Gets the party ID.

```csharp
public ulong? PartyId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordRichPresence_SmallImage"></a>SmallImage

Gets the small image for the rich presence.

```csharp
public DiscordAsset SmallImage { get; }
```

#### Property Value

[DiscordAsset](DSharpPlus.Entities.DiscordAsset.md)

### <a id="DSharpPlus_Entities_DiscordRichPresence_SmallImageText"></a>SmallImageText

Gets the hovertext for small image.

```csharp
public string SmallImageText { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRichPresence_SpectateSecret"></a>SpectateSecret

Gets the secret value enabling users to spectate your game.

```csharp
public string SpectateSecret { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRichPresence_StartTimestamp"></a>StartTimestamp

Gets the game start timestamp.

```csharp
public DateTimeOffset? StartTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordRichPresence_State"></a>State

Gets the game state.

```csharp
public string State { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

