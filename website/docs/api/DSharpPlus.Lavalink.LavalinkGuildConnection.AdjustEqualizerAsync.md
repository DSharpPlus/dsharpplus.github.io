# Method AdjustEqualizerAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_AdjustEqualizerAsync_DSharpPlus_Lavalink_LavalinkBandAdjustment___"></a>AdjustEqualizerAsync\(params LavalinkBandAdjustment\[\]\)

Adjusts the specified bands in the audio equalizer. This will alter the sound output, and might incur a lot of CPU usage.

```csharp
public Task AdjustEqualizerAsync(params LavalinkBandAdjustment[] bands)
```

### Parameters

`bands` [LavalinkBandAdjustment](DSharpPlus.Lavalink.LavalinkBandAdjustment.md)\[\]

Bands adjustments to make. You must specify one adjustment per band at most.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

