# Method InstallFilter

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_VoiceTransmitSink_InstallFilter_DSharpPlus_VoiceNext_IVoiceFilter_System_Int32_"></a>InstallFilter\(IVoiceFilter, int\)

Installs a new PCM filter, with specified execution order.

```csharp
public void InstallFilter(IVoiceFilter filter, int order = 2147483647)
```

### Parameters

`filter` [IVoiceFilter](DSharpPlus.VoiceNext.IVoiceFilter.md)

Filter to install.

`order` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Order of the new filter. This determines where the filter will be inserted in the filter pipeline.

