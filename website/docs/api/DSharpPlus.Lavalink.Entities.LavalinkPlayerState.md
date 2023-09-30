# Class LavalinkPlayerState

Namespace: [DSharpPlus.Lavalink.Entities](DSharpPlus.Lavalink.Entities.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents current state of given player.

```csharp
public sealed class LavalinkPlayerState
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkPlayerState](DSharpPlus.Lavalink.Entities.LavalinkPlayerState.md)

## Properties

### <a id="DSharpPlus_Lavalink_Entities_LavalinkPlayerState_CurrentTrack"></a>CurrentTrack

Gets the currently-played track.

```csharp
public LavalinkTrack CurrentTrack { get; }
```

#### Property Value

[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkPlayerState_LastUpdate"></a>LastUpdate

Gets the timestamp at which this state was last updated.

```csharp
public DateTimeOffset LastUpdate { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkPlayerState_PlaybackPosition"></a>PlaybackPosition

Gets the current playback position.

```csharp
public TimeSpan PlaybackPosition { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

