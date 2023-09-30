# Method GetMaximumBufferSize

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_AudioFormat_GetMaximumBufferSize"></a>GetMaximumBufferSize\(\)

Gets the maximum buffer size for decoding. This method should be called when decoding Opus data to PCM, to ensure sufficient buffer size.

```csharp
public int GetMaximumBufferSize()
```

### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Buffer size required to decode data.

