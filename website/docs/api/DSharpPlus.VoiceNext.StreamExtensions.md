# Class StreamExtensions

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

```csharp
public static class StreamExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[StreamExtensions](DSharpPlus.VoiceNext.StreamExtensions.md)

## Methods

### <a id="DSharpPlus_VoiceNext_StreamExtensions_CopyToAsync_System_IO_Stream_DSharpPlus_VoiceNext_VoiceTransmitSink_System_Nullable_System_Int32__System_Threading_CancellationToken_"></a>CopyToAsync\(Stream, VoiceTransmitSink, int?, CancellationToken\)

Asynchronously reads the bytes from the current stream and writes them to the specified <xref href="DSharpPlus.VoiceNext.VoiceTransmitSink" data-throw-if-not-resolved="false"></xref>.

```csharp
public static Task CopyToAsync(this Stream source, VoiceTransmitSink destination, int? bufferSize = null, CancellationToken cancellationToken = default)
```

#### Parameters

`source` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The source <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref>

`destination` [VoiceTransmitSink](DSharpPlus.VoiceNext.VoiceTransmitSink.md)

The target <xref href="DSharpPlus.VoiceNext.VoiceTransmitSink" data-throw-if-not-resolved="false"></xref>

`bufferSize` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The size, in bytes, of the buffer. This value must be greater than zero. If <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a>, defaults to the packet size specified by <code class="paramref">destination</code>.

`cancellationToken` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

The token to monitor for cancellation requests.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

