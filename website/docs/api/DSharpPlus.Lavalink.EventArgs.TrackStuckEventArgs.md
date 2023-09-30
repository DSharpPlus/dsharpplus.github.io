# Class TrackStuckEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents event arguments for a track stuck event.

```csharp
public sealed class TrackStuckEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[TrackStuckEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStuckEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_TrackStuckEventArgs_Player"></a>Player

Gets the player that got stuck.

```csharp
public LavalinkGuildConnection Player { get; }
```

#### Property Value

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

### <a id="DSharpPlus_Lavalink_EventArgs_TrackStuckEventArgs_ThresholdMilliseconds"></a>ThresholdMilliseconds

Gets the millisecond threshold for the stuck event.

```csharp
public long ThresholdMilliseconds { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_Lavalink_EventArgs_TrackStuckEventArgs_Track"></a>Track

Gets the track that got stuck.

```csharp
public LavalinkTrack Track { get; }
```

#### Property Value

[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

