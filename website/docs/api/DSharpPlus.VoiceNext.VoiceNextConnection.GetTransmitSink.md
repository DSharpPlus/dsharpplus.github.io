# Method GetTransmitSink

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_VoiceNextConnection_GetTransmitSink_System_Int32_"></a>GetTransmitSink\(int\)

Gets a transmit stream for this connection, optionally specifying a packet size to use with the stream. If a stream is already configured, it will return the existing one.

```csharp
public VoiceTransmitSink GetTransmitSink(int sampleDuration = 20)
```

### Parameters

`sampleDuration` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Duration, in ms, to use for audio packets.

### Returns

[VoiceTransmitSink](DSharpPlus.VoiceNext.VoiceTransmitSink.md)

Transmit stream.

