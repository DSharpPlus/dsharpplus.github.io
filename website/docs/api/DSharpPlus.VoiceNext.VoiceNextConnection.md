# Class VoiceNextConnection

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

VoiceNext connection to a voice channel.

```csharp
public sealed class VoiceNextConnection
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md)

## Properties

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_AudioFormat"></a>AudioFormat

Gets the audio format used by the Opus encoder.

```csharp
public AudioFormat AudioFormat { get; }
```

#### Property Value

[AudioFormat](DSharpPlus.VoiceNext.AudioFormat.md)

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_IsPlaying"></a>IsPlaying

Gets whether this connection is still playing audio.

```csharp
public bool IsPlaying { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_TargetChannel"></a>TargetChannel

Gets the channel this voice client is connected to.

```csharp
public DiscordChannel TargetChannel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_UdpPing"></a>UdpPing

Gets the UDP round-trip time in ms.

```csharp
public int UdpPing { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_WebSocketPing"></a>WebSocketPing

Gets the websocket round-trip time in ms.

```csharp
public int WebSocketPing { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_Disconnect"></a>Disconnect\(\)

Disconnects and disposes this voice connection.

```csharp
public void Disconnect()
```

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_Dispose"></a>Dispose\(\)

Disconnects and disposes this voice connection.

```csharp
public void Dispose()
```

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_GetTransmitSink_System_Int32_"></a>GetTransmitSink\(int\)

Gets a transmit stream for this connection, optionally specifying a packet size to use with the stream. If a stream is already configured, it will return the existing one.

```csharp
public VoiceTransmitSink GetTransmitSink(int sampleDuration = 20)
```

#### Parameters

`sampleDuration` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Duration, in ms, to use for audio packets.

#### Returns

[VoiceTransmitSink](DSharpPlus.VoiceNext.VoiceTransmitSink.md)

Transmit stream.

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_Pause"></a>Pause\(\)

Pauses playback.

```csharp
public void Pause()
```

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_ResumeAsync"></a>ResumeAsync\(\)

Asynchronously resumes playback.

```csharp
public Task ResumeAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_SendSpeakingAsync_System_Boolean_"></a>SendSpeakingAsync\(bool\)

Sends a speaking status to the connected voice channel.

```csharp
public Task SendSpeakingAsync(bool speaking = true)
```

#### Parameters

`speaking` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the current user is speaking or not.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the sending operation.

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_WaitForPlaybackFinishAsync"></a>WaitForPlaybackFinishAsync\(\)

Asynchronously waits for playback to be finished. Playback is finished when speaking = false is signalled.

```csharp
public Task WaitForPlaybackFinishAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the waiting operation.

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_UserJoined"></a>UserJoined

Triggered whenever a user joins voice in the connected guild.

```csharp
public event AsyncEventHandler<VoiceNextConnection, VoiceUserJoinEventArgs> UserJoined
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md), [VoiceUserJoinEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceUserJoinEventArgs.md)\>

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_UserLeft"></a>UserLeft

Triggered whenever a user leaves voice in the connected guild.

```csharp
public event AsyncEventHandler<VoiceNextConnection, VoiceUserLeaveEventArgs> UserLeft
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md), [VoiceUserLeaveEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceUserLeaveEventArgs.md)\>

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_UserSpeaking"></a>UserSpeaking

Triggered whenever a user speaks in the connected voice channel.

```csharp
public event AsyncEventHandler<VoiceNextConnection, UserSpeakingEventArgs> UserSpeaking
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md), [UserSpeakingEventArgs](DSharpPlus.EventArgs.UserSpeakingEventArgs.md)\>

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_VoiceReceived"></a>VoiceReceived

Triggered whenever voice data is received from the connected voice channel.

```csharp
public event AsyncEventHandler<VoiceNextConnection, VoiceReceiveEventArgs> VoiceReceived
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md), [VoiceReceiveEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceReceiveEventArgs.md)\>

### <a id="DSharpPlus_VoiceNext_VoiceNextConnection_VoiceSocketErrored"></a>VoiceSocketErrored

Triggered whenever voice WebSocket throws an exception.

```csharp
public event AsyncEventHandler<VoiceNextConnection, SocketErrorEventArgs> VoiceSocketErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md), [SocketErrorEventArgs](DSharpPlus.EventArgs.SocketErrorEventArgs.md)\>

