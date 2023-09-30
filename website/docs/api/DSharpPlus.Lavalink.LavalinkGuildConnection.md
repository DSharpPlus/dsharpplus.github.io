# Class LavalinkGuildConnection

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents a Lavalink connection to a channel.

```csharp
public sealed class LavalinkGuildConnection
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_Channel"></a>Channel

Gets the voice channel associated with this connection.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_CurrentState"></a>CurrentState

Gets the current player state.

```csharp
public LavalinkPlayerState CurrentState { get; }
```

#### Property Value

[LavalinkPlayerState](DSharpPlus.Lavalink.Entities.LavalinkPlayerState.md)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_Guild"></a>Guild

Gets the guild associated with this connection.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_IsConnected"></a>IsConnected

Gets whether this channel is still connected.

```csharp
public bool IsConnected { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_Node"></a>Node

Gets the Lavalink node associated with this connection.

```csharp
public LavalinkNodeConnection Node { get; }
```

#### Property Value

[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

## Methods

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_AdjustEqualizerAsync_DSharpPlus_Lavalink_LavalinkBandAdjustment___"></a>AdjustEqualizerAsync\(params LavalinkBandAdjustment\[\]\)

Adjusts the specified bands in the audio equalizer. This will alter the sound output, and might incur a lot of CPU usage.

```csharp
public Task AdjustEqualizerAsync(params LavalinkBandAdjustment[] bands)
```

#### Parameters

`bands` [LavalinkBandAdjustment](DSharpPlus.Lavalink.LavalinkBandAdjustment.md)\[\]

Bands adjustments to make. You must specify one adjustment per band at most.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_DisconnectAsync_System_Boolean_"></a>DisconnectAsync\(bool\)

Disconnects the connection from the voice channel.

```csharp
public Task DisconnectAsync(bool shouldDestroy = true)
```

#### Parameters

`shouldDestroy` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the connection should be destroyed on the Lavalink server when leaving.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_GetTracksAsync_System_String_DSharpPlus_Lavalink_LavalinkSearchType_"></a>GetTracksAsync\(string, LavalinkSearchType\)

Searches for specified terms.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(string searchQuery, LavalinkSearchType type = LavalinkSearchType.Youtube)
```

#### Parameters

`searchQuery` [string](https://learn.microsoft.com/dotnet/api/system.string)

What to search for.

`type` [LavalinkSearchType](DSharpPlus.Lavalink.LavalinkSearchType.md)

What platform will search for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks matching the criteria.

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_GetTracksAsync_System_Uri_"></a>GetTracksAsync\(Uri\)

Loads tracks from specified URL.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(Uri uri)
```

#### Parameters

`uri` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

URL to load tracks from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks from the URL.

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_GetTracksAsync_System_IO_FileInfo_"></a>GetTracksAsync\(FileInfo\)

Loads tracks from a local file.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(FileInfo file)
```

#### Parameters

`file` [FileInfo](https://learn.microsoft.com/dotnet/api/system.io.fileinfo)

File to load tracks from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks from the file.

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_PauseAsync"></a>PauseAsync\(\)

Pauses the player.

```csharp
public Task PauseAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_PlayAsync_DSharpPlus_Lavalink_LavalinkTrack_"></a>PlayAsync\(LavalinkTrack\)

Queues the specified track for playback.

```csharp
public Task PlayAsync(LavalinkTrack track)
```

#### Parameters

`track` [LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

Track to play.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_PlayPartialAsync_DSharpPlus_Lavalink_LavalinkTrack_System_TimeSpan_System_TimeSpan_"></a>PlayPartialAsync\(LavalinkTrack, TimeSpan, TimeSpan\)

Queues the specified track for playback. The track will be played from specified start timestamp to specified end timestamp.

```csharp
public Task PlayPartialAsync(LavalinkTrack track, TimeSpan start, TimeSpan end)
```

#### Parameters

`track` [LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

Track to play.

`start` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Timestamp to start playback at.

`end` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Timestamp to stop playback at.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_ResetEqualizerAsync"></a>ResetEqualizerAsync\(\)

Resets the audio equalizer to default values.

```csharp
public Task ResetEqualizerAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_ResumeAsync"></a>ResumeAsync\(\)

Resumes playback.

```csharp
public Task ResumeAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_SeekAsync_System_TimeSpan_"></a>SeekAsync\(TimeSpan\)

Seeks the current track to specified position.

```csharp
public Task SeekAsync(TimeSpan position)
```

#### Parameters

`position` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Position to seek to.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_SetVolumeAsync_System_Int32_"></a>SetVolumeAsync\(int\)

Sets the playback volume. This might incur a lot of CPU usage.

```csharp
public Task SetVolumeAsync(int volume)
```

#### Parameters

`volume` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Volume to set. Needs to be greater or equal to 0, and less than or equal to 100. 100 means 100% and is the default value.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_StopAsync"></a>StopAsync\(\)

Stops the player completely.

```csharp
public Task StopAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_DiscordWebSocketClosed"></a>DiscordWebSocketClosed

Triggered whenever Discord Voice WebSocket connection is terminated.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, WebSocketCloseEventArgs> DiscordWebSocketClosed
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [WebSocketCloseEventArgs](DSharpPlus.Lavalink.EventArgs.WebSocketCloseEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_PlaybackFinished"></a>PlaybackFinished

Triggered whenever playback of a track finishes.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackFinishEventArgs> PlaybackFinished
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackFinishEventArgs](DSharpPlus.Lavalink.EventArgs.TrackFinishEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_PlaybackStarted"></a>PlaybackStarted

Triggered whenever playback of a track starts.
<p>This is only available for version 3.3.1 and greater.</p>

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackStartEventArgs> PlaybackStarted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackStartEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStartEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_PlayerUpdated"></a>PlayerUpdated

Triggered whenever Lavalink updates player status.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, PlayerUpdateEventArgs> PlayerUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [PlayerUpdateEventArgs](DSharpPlus.Lavalink.EventArgs.PlayerUpdateEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_TrackException"></a>TrackException

Triggered whenever playback of a track encounters an error.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackExceptionEventArgs> TrackException
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackExceptionEventArgs](DSharpPlus.Lavalink.EventArgs.TrackExceptionEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_TrackStuck"></a>TrackStuck

Triggered whenever playback of a track gets stuck.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackStuckEventArgs> TrackStuck
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackStuckEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStuckEventArgs.md)\>

