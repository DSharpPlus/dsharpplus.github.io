# Class TrackStartEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents arguments for a track playback start event.

```csharp
public sealed class TrackStartEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[TrackStartEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStartEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_TrackStartEventArgs_Player"></a>Player

Gets the player that started playback.

```csharp
public LavalinkGuildConnection Player { get; }
```

#### Property Value

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

### <a id="DSharpPlus_Lavalink_EventArgs_TrackStartEventArgs_Track"></a>Track

Gets the track that started playing.

```csharp
public LavalinkTrack Track { get; }
```

#### Property Value

[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

