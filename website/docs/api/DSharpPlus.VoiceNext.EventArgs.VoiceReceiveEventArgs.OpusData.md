# Property OpusData

Namespace: [DSharpPlus.VoiceNext.EventArgs](DSharpPlus.VoiceNext.EventArgs.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_EventArgs_VoiceReceiveEventArgs_OpusData"></a>OpusData

Gets the received voice data, in Opus format. Note that for packets that were lost and/or compensated for, this will be empty.

```csharp
public ReadOnlyMemory<byte> OpusData { get; }
```

### Property Value

[ReadOnlyMemory](https://learn.microsoft.com/dotnet/api/system.readonlymemory\-1)<[byte](https://learn.microsoft.com/dotnet/api/system.byte)\>

