# Class LavalinkStatistics

Namespace: [DSharpPlus.Lavalink.Entities](DSharpPlus.Lavalink.Entities.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents statistics of Lavalink resource usage.

```csharp
public sealed class LavalinkStatistics
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkStatistics](DSharpPlus.Lavalink.Entities.LavalinkStatistics.md)

## Properties

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_ActivePlayers"></a>ActivePlayers

Gets the number of currently-playing players.

```csharp
public int ActivePlayers { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_AverageDeficitFramesPerMinute"></a>AverageDeficitFramesPerMinute

Gets the average frame deficit per minute.

```csharp
public int AverageDeficitFramesPerMinute { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_AverageNulledFramesPerMinute"></a>AverageNulledFramesPerMinute

Gets the average number of frames that were sent as null per minute.

```csharp
public int AverageNulledFramesPerMinute { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_AverageSentFramesPerMinute"></a>AverageSentFramesPerMinute

Gets the average number of sent frames per minute.

```csharp
public int AverageSentFramesPerMinute { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_CpuCoreCount"></a>CpuCoreCount

Gets the number of CPU cores available.

```csharp
public int CpuCoreCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_CpuLavalinkLoad"></a>CpuLavalinkLoad

Gets the total % of CPU resources used by lavalink.

```csharp
public double CpuLavalinkLoad { get; }
```

#### Property Value

[double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_CpuSystemLoad"></a>CpuSystemLoad

Gets the total % of CPU resources in use on the system.

```csharp
public double CpuSystemLoad { get; }
```

#### Property Value

[double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_RamAllocated"></a>RamAllocated

Gets the amount of allocated RAM, in bytes.

```csharp
public long RamAllocated { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_RamFree"></a>RamFree

Gets the amount of free RAM, in bytes.

```csharp
public long RamFree { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_RamReservable"></a>RamReservable

Gets the amount of reservable RAM, in bytes.

```csharp
public long RamReservable { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_RamUsed"></a>RamUsed

Gets the amount of used RAM, in bytes.

```csharp
public long RamUsed { get; }
```

#### Property Value

[long](https://learn.microsoft.com/dotnet/api/system.int64)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_TotalPlayers"></a>TotalPlayers

Gets the total number of players.

```csharp
public int TotalPlayers { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_Entities_LavalinkStatistics_Uptime"></a>Uptime

Gets the node uptime.

```csharp
public TimeSpan Uptime { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

