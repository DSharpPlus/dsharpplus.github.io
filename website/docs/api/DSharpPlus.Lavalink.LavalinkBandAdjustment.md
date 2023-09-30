# Struct LavalinkBandAdjustment

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents Lavalink equalizer band adjustment. This is used to alter the sound output by using Lavalink's equalizer.

```csharp
public struct LavalinkBandAdjustment
```

## Constructors

### <a id="DSharpPlus_Lavalink_LavalinkBandAdjustment__ctor_System_Int32_System_Single_"></a>LavalinkBandAdjustment\(int, float\)

Creates a new band adjustment with specified parameters.

```csharp
public LavalinkBandAdjustment(int bandId, float gain)
```

#### Parameters

`bandId` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Which band to adjust. Must be in 0-14 range.

`gain` [float](https://learn.microsoft.com/dotnet/api/system.single)

By how much to adjust the band. Must be greater than or equal to -0.25 (muted), and less than or equal to +1.0. +0.25 means the band is doubled.

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkBandAdjustment_BandId"></a>BandId

Gets the ID of the band to adjust.

```csharp
[JsonProperty("band")]
public readonly int BandId { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_LavalinkBandAdjustment_Gain"></a>Gain

Gets the gain of the specified band.

```csharp
[JsonProperty("gain")]
public readonly float Gain { get; }
```

#### Property Value

[float](https://learn.microsoft.com/dotnet/api/system.single)

