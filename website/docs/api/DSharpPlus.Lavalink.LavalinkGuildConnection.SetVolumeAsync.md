# Method SetVolumeAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkGuildConnection_SetVolumeAsync_System_Int32_"></a>SetVolumeAsync\(int\)

Sets the playback volume. This might incur a lot of CPU usage.

```csharp
public Task SetVolumeAsync(int volume)
```

### Parameters

`volume` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Volume to set. Needs to be greater or equal to 0, and less than or equal to 100. 100 means 100% and is the default value.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

