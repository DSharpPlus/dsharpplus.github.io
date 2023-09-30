# Enum TrackEndReason

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents a reason why a track finished playing.

```csharp
public enum TrackEndReason
```

###### Extension Methods

[ExtensionMethods.GetName<TrackEndReason\>\(TrackEndReason\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_), 
[LavalinkUtilities.MayStartNext\(TrackEndReason\)](DSharpPlus.Lavalink.LavalinkUtilities.md\#DSharpPlus\_Lavalink\_LavalinkUtilities\_MayStartNext\_DSharpPlus\_Lavalink\_EventArgs\_TrackEndReason\_)

## Fields

`Cleanup = 4` 

The track was stopped because the cleanup threshold for the audio player was reached. This triggers when the amount
of time passed since the last call to AudioPlayer#provide() has reached the threshold specified in player manager
configuration. This may also indicate either a leaked audio player which was discarded, but not stopped.

`Finished = 0` 

This means that the track itself emitted a terminator. This is usually caused by the track reaching the end,
however it will also be used when it ends due to an exception.

`LoadFailed = 1` 

This means that the track failed to start, throwing an exception before providing any audio.

`Replaced = 3` 

The track stopped playing because a new track started playing. Note that with this reason, the old track will still
play until either its buffer runs out or audio from the new track is available.

`Stopped = 2` 

The track was stopped due to the player being stopped by either calling stop() or playTrack(null).

