# Constructor AudioFormat

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_AudioFormat__ctor_System_Int32_System_Int32_DSharpPlus_VoiceNext_VoiceApplication_"></a>AudioFormat\(int, int, VoiceApplication\)

Creates a new audio format for use with Opus encoder.

```csharp
public AudioFormat(int sampleRate = 48000, int channelCount = 2, VoiceApplication voiceApplication = VoiceApplication.Music)
```

### Parameters

`sampleRate` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Audio sampling rate in Hz.

`channelCount` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of audio channels in the data.

`voiceApplication` [VoiceApplication](DSharpPlus.VoiceNext.VoiceApplication.md)

Encoder preset to use.

