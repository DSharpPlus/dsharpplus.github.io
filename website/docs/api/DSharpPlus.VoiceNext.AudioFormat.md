# Struct AudioFormat

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

Defines the format of PCM data consumed or produced by Opus.

```csharp
public struct AudioFormat
```

## Constructors

### <a id="DSharpPlus_VoiceNext_AudioFormat__ctor_System_Int32_System_Int32_DSharpPlus_VoiceNext_VoiceApplication_"></a>AudioFormat\(int, int, VoiceApplication\)

Creates a new audio format for use with Opus encoder.

```csharp
public AudioFormat(int sampleRate = 48000, int channelCount = 2, VoiceApplication voiceApplication = VoiceApplication.Music)
```

#### Parameters

`sampleRate` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Audio sampling rate in Hz.

`channelCount` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of audio channels in the data.

`voiceApplication` [VoiceApplication](DSharpPlus.VoiceNext.VoiceApplication.md)

Encoder preset to use.

## Properties

### <a id="DSharpPlus_VoiceNext_AudioFormat_AllowedChannelCounts"></a>AllowedChannelCounts

Gets the collection of channel counts the Opus encoder can use.

```csharp
public static IReadOnlyCollection<int> AllowedChannelCounts { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="DSharpPlus_VoiceNext_AudioFormat_AllowedSampleDurations"></a>AllowedSampleDurations

Gets the collection of sample durations (in ms) the Opus encoder can use.

```csharp
public static IReadOnlyCollection<int> AllowedSampleDurations { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="DSharpPlus_VoiceNext_AudioFormat_AllowedSampleRates"></a>AllowedSampleRates

Gets the collection of sampling rates (in Hz) the Opus encoder can use.

```csharp
public static IReadOnlyCollection<int> AllowedSampleRates { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="DSharpPlus_VoiceNext_AudioFormat_ChannelCount"></a>ChannelCount

Gets the audio channel count.

```csharp
public readonly int ChannelCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_VoiceNext_AudioFormat_Default"></a>Default

Gets the default audio format. This is a format configured for 48kHz sampling rate, 2 channels, with music quality preset.

```csharp
public static AudioFormat Default { get; }
```

#### Property Value

[AudioFormat](DSharpPlus.VoiceNext.AudioFormat.md)

### <a id="DSharpPlus_VoiceNext_AudioFormat_SampleRate"></a>SampleRate

Gets the audio sampling rate in Hz.

```csharp
public readonly int SampleRate { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_VoiceNext_AudioFormat_VoiceApplication"></a>VoiceApplication

Gets the voice application, which dictates the quality preset.

```csharp
public readonly VoiceApplication VoiceApplication { get; }
```

#### Property Value

[VoiceApplication](DSharpPlus.VoiceNext.VoiceApplication.md)

## Methods

### <a id="DSharpPlus_VoiceNext_AudioFormat_CalculateSampleSize_System_Int32_"></a>CalculateSampleSize\(int\)

Calculates a sample size in bytes.

```csharp
public int CalculateSampleSize(int sampleDuration)
```

#### Parameters

`sampleDuration` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Millisecond duration of a sample.

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Calculated sample size in bytes.

### <a id="DSharpPlus_VoiceNext_AudioFormat_GetMaximumBufferSize"></a>GetMaximumBufferSize\(\)

Gets the maximum buffer size for decoding. This method should be called when decoding Opus data to PCM, to ensure sufficient buffer size.

```csharp
public int GetMaximumBufferSize()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Buffer size required to decode data.

