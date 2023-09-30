# Method WriteAsync

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_WriteAsync_System_Byte___System_Int32_System_Int32_System_Threading_CancellationToken_"></a>WriteAsync\(byte\[\], int, int, CancellationToken\)

Writes PCM data to the sink. The data is prepared for transmission, and enqueued.

```csharp
public Task WriteAsync(byte[] buffer, int offset, int count, CancellationToken cancellationToken = default)
```

### Parameters

`buffer` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

PCM data buffer to send.

`offset` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Start of the data in the buffer.

`count` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of bytes from the buffer.

`cancellationToken` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

The token to monitor for cancellation requests.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_WriteAsync_System_ReadOnlyMemory_System_Byte__System_Threading_CancellationToken_"></a>WriteAsync\(ReadOnlyMemory<byte\>, CancellationToken\)

Writes PCM data to the sink. The data is prepared for transmission, and enqueued.

```csharp
public Task WriteAsync(ReadOnlyMemory<byte> buffer, CancellationToken cancellationToken = default)
```

### Parameters

`buffer` [ReadOnlyMemory](https://learn.microsoft.com/dotnet/api/system.readonlymemory\-1)<[byte](https://learn.microsoft.com/dotnet/api/system.byte)\>

PCM data buffer to send.

`cancellationToken` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

The token to monitor for cancellation requests.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

