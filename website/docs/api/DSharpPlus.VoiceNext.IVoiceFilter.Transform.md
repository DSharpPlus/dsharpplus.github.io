# Method Transform

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_IVoiceFilter_Transform_System_Span_System_Int16__DSharpPlus_VoiceNext_AudioFormat_System_Int32_"></a>Transform\(Span<short\>, AudioFormat, int\)

Transforms the supplied PCM data using this filter.

```csharp
void Transform(Span<short> pcmData, AudioFormat pcmFormat, int duration)
```

### Parameters

`pcmData` [Span](https://learn.microsoft.com/dotnet/api/system.span\-1)<[short](https://learn.microsoft.com/dotnet/api/system.int16)\>

PCM data to transform. The transformation happens in-place.

`pcmFormat` [AudioFormat](DSharpPlus.VoiceNext.AudioFormat.md)

Format of the supplied PCM data.

`duration` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Millisecond duration of the supplied PCM data.

