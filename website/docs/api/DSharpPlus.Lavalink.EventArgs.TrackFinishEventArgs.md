# Class TrackFinishEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents arguments for a track playback finish event.

```csharp
public sealed class TrackFinishEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[TrackFinishEventArgs](DSharpPlus.Lavalink.EventArgs.TrackFinishEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_TrackFinishEventArgs_Player"></a>Player

Gets the player that finished playback.

```csharp
public LavalinkGuildConnection Player { get; }
```

#### Property Value

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

### <a id="DSharpPlus_Lavalink_EventArgs_TrackFinishEventArgs_Reason"></a>Reason

Gets the reason why the track stopped playing.

```csharp
public TrackEndReason Reason { get; }
```

#### Property Value

[TrackEndReason](DSharpPlus.Lavalink.EventArgs.TrackEndReason.md)

### <a id="DSharpPlus_Lavalink_EventArgs_TrackFinishEventArgs_Track"></a>Track

Gets the track that finished playing.

```csharp
public LavalinkTrack Track { get; }
```

#### Property Value

[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

