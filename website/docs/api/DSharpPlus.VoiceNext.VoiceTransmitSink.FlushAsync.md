# Method FlushAsync

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_FlushAsync_System_Threading_CancellationToken_"></a>FlushAsync\(CancellationToken\)

Flushes the rest of the PCM data in this buffer to VoiceNext packet queue.

```csharp
public Task FlushAsync(CancellationToken cancellationToken = default)
```

### Parameters

`cancellationToken` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

The token to monitor for cancellation requests.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

