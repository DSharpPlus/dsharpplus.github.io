# Class PlayerUpdateEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents arguments for player update event.

```csharp
public sealed class PlayerUpdateEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[PlayerUpdateEventArgs](DSharpPlus.Lavalink.EventArgs.PlayerUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_PlayerUpdateEventArgs_Player"></a>Player

Gets the player that emitted this event.

```csharp
public LavalinkGuildConnection Player { get; }
```

#### Property Value

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

### <a id="DSharpPlus_Lavalink_EventArgs_PlayerUpdateEventArgs_Position"></a>Position

Gets the position in the playback stream.

```csharp
public TimeSpan Position { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

### <a id="DSharpPlus_Lavalink_EventArgs_PlayerUpdateEventArgs_Timestamp"></a>Timestamp

Gets the timestamp at which this event was emitted.

```csharp
public DateTimeOffset Timestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

