# Class TrackExceptionEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents event arguments for a track exception event.

```csharp
public sealed class TrackExceptionEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[TrackExceptionEventArgs](DSharpPlus.Lavalink.EventArgs.TrackExceptionEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_TrackExceptionEventArgs_Error"></a>Error

Gets the error that occurred during playback.

```csharp
public string Error { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_EventArgs_TrackExceptionEventArgs_Player"></a>Player

Gets the player that got stuck.

```csharp
public LavalinkGuildConnection Player { get; }
```

#### Property Value

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

### <a id="DSharpPlus_Lavalink_EventArgs_TrackExceptionEventArgs_Track"></a>Track

Gets the track that got stuck.

```csharp
public LavalinkTrack Track { get; }
```

#### Property Value

[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

