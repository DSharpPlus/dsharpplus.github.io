# Class VoiceTransmitSink

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

Sink used to transmit audio data via <xref href="DSharpPlus.VoiceNext.VoiceNextConnection" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class VoiceTransmitSink
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[VoiceTransmitSink](DSharpPlus.VoiceNext.VoiceTransmitSink.md)

## Properties

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_SampleDuration"></a>SampleDuration

Gets the PCM sample duration for this sink.

```csharp
public int SampleDuration { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_SampleLength"></a>SampleLength

Gets the length of the PCM buffer for this sink.
Written packets should adhere to this size, but the sink will adapt to fit.

```csharp
public int SampleLength { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_VolumeModifier"></a>VolumeModifier

Gets or sets the volume modifier for this sink. Changing this will alter the volume of the output. 1.0 is 100%.

```csharp
public double VolumeModifier { get; set; }
```

#### Property Value

[double](https://learn.microsoft.com/dotnet/api/system.double)

## Methods

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_Dispose"></a>Dispose\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

```csharp
public void Dispose()
```

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_FlushAsync_System_Threading_CancellationToken_"></a>FlushAsync\(CancellationToken\)

Flushes the rest of the PCM data in this buffer to VoiceNext packet queue.

```csharp
public Task FlushAsync(CancellationToken cancellationToken = default)
```

#### Parameters

`cancellationToken` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

The token to monitor for cancellation requests.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_GetInstalledFilters"></a>GetInstalledFilters\(\)

Gets the collection of installed PCM filters, in order of their execution.

```csharp
public IEnumerable<IVoiceFilter> GetInstalledFilters()
```

#### Returns

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[IVoiceFilter](DSharpPlus.VoiceNext.IVoiceFilter.md)\>

Installed PCM filters, in order of execution.

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_InstallFilter_DSharpPlus_VoiceNext_IVoiceFilter_System_Int32_"></a>InstallFilter\(IVoiceFilter, int\)

Installs a new PCM filter, with specified execution order.

```csharp
public void InstallFilter(IVoiceFilter filter, int order = 2147483647)
```

#### Parameters

`filter` [IVoiceFilter](DSharpPlus.VoiceNext.IVoiceFilter.md)

Filter to install.

`order` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Order of the new filter. This determines where the filter will be inserted in the filter pipeline.

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_Pause"></a>Pause\(\)

Pauses playback.

```csharp
public void Pause()
```

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_ResumeAsync"></a>ResumeAsync\(\)

Resumes playback.

```csharp
public Task ResumeAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_UninstallFilter_DSharpPlus_VoiceNext_IVoiceFilter_"></a>UninstallFilter\(IVoiceFilter\)

Uninstalls an installed PCM filter.

```csharp
public bool UninstallFilter(IVoiceFilter filter)
```

#### Parameters

`filter` [IVoiceFilter](DSharpPlus.VoiceNext.IVoiceFilter.md)

Filter to uninstall.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the filter was uninstalled.

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_WriteAsync_System_Byte___System_Int32_System_Int32_System_Threading_CancellationToken_"></a>WriteAsync\(byte\[\], int, int, CancellationToken\)

Writes PCM data to the sink. The data is prepared for transmission, and enqueued.

```csharp
public Task WriteAsync(byte[] buffer, int offset, int count, CancellationToken cancellationToken = default)
```

#### Parameters

`buffer` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

PCM data buffer to send.

`offset` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Start of the data in the buffer.

`count` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of bytes from the buffer.

`cancellationToken` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

The token to monitor for cancellation requests.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_WriteAsync_System_ReadOnlyMemory_System_Byte__System_Threading_CancellationToken_"></a>WriteAsync\(ReadOnlyMemory<byte\>, CancellationToken\)

Writes PCM data to the sink. The data is prepared for transmission, and enqueued.

```csharp
public Task WriteAsync(ReadOnlyMemory<byte> buffer, CancellationToken cancellationToken = default)
```

#### Parameters

`buffer` [ReadOnlyMemory](https://learn.microsoft.com/dotnet/api/system.readonlymemory\-1)<[byte](https://learn.microsoft.com/dotnet/api/system.byte)\>

PCM data buffer to send.

`cancellationToken` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

The token to monitor for cancellation requests.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

