# Method PlayPartialAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_PlayPartialAsync_DSharpPlus_Lavalink_LavalinkTrack_System_TimeSpan_System_TimeSpan_"></a>PlayPartialAsync\(LavalinkTrack, TimeSpan, TimeSpan\)

Queues the specified track for playback. The track will be played from specified start timestamp to specified end timestamp.

```csharp
public Task PlayPartialAsync(LavalinkTrack track, TimeSpan start, TimeSpan end)
```

### Parameters

`track` [LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

Track to play.

`start` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Timestamp to start playback at.

`end` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Timestamp to stop playback at.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

