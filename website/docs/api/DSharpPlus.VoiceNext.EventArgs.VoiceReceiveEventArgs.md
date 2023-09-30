# Class VoiceReceiveEventArgs

Namespace: [DSharpPlus.VoiceNext.EventArgs](DSharpPlus.VoiceNext.EventArgs.md)  
Assembly: DSharpPlus.VoiceNext.dll

Represents arguments for VoiceReceived events.

```csharp
public class VoiceReceiveEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[VoiceReceiveEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceReceiveEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceReceiveEventArgs_AudioDuration"></a>AudioDuration

Gets the millisecond duration of the PCM audio sample.

```csharp
public int AudioDuration { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceReceiveEventArgs_AudioFormat"></a>AudioFormat

Gets the format of the received PCM data.
<p>
Important: This isn't always the format set in <xref href="DSharpPlus.VoiceNext.VoiceNextConfiguration.AudioFormat" data-throw-if-not-resolved="false"></xref>, and depends on the audio data received.
</p>

```csharp
public AudioFormat AudioFormat { get; }
```

#### Property Value

[AudioFormat](DSharpPlus.VoiceNext.AudioFormat.md)

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceReceiveEventArgs_OpusData"></a>OpusData

Gets the received voice data, in Opus format. Note that for packets that were lost and/or compensated for, this will be empty.

```csharp
public ReadOnlyMemory<byte> OpusData { get; }
```

#### Property Value

[ReadOnlyMemory](https://learn.microsoft.com/dotnet/api/system.readonlymemory\-1)<[byte](https://learn.microsoft.com/dotnet/api/system.byte)\>

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceReceiveEventArgs_PcmData"></a>PcmData

Gets the received voice data, decoded to PCM format.

```csharp
public ReadOnlyMemory<byte> PcmData { get; }
```

#### Property Value

[ReadOnlyMemory](https://learn.microsoft.com/dotnet/api/system.readonlymemory\-1)<[byte](https://learn.microsoft.com/dotnet/api/system.byte)\>

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceReceiveEventArgs_SSRC"></a>SSRC

Gets the SSRC of the audio source.

```csharp
public uint SSRC { get; }
```

#### Property Value

[uint](https://learn.microsoft.com/dotnet/api/system.uint32)

### <a id="DSharpPlus_VoiceNext_EventArgs_VoiceReceiveEventArgs_User"></a>User

Gets the user that sent the audio data.

```csharp
public DiscordUser? User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)?

