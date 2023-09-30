# Class VoiceNextConfiguration

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

VoiceNext client configuration.

```csharp
public sealed class VoiceNextConfiguration
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[VoiceNextConfiguration](DSharpPlus.VoiceNext.VoiceNextConfiguration.md)

## Constructors

### <a id="DSharpPlus_VoiceNext_VoiceNextConfiguration__ctor"></a>VoiceNextConfiguration\(\)

Creates a new instance of <xref href="DSharpPlus.VoiceNext.VoiceNextConfiguration" data-throw-if-not-resolved="false"></xref>.

```csharp
public VoiceNextConfiguration()
```

### <a id="DSharpPlus_VoiceNext_VoiceNextConfiguration__ctor_DSharpPlus_VoiceNext_VoiceNextConfiguration_"></a>VoiceNextConfiguration\(VoiceNextConfiguration\)

Creates a new instance of <xref href="DSharpPlus.VoiceNext.VoiceNextConfiguration" data-throw-if-not-resolved="false"></xref>, copying the properties of another configuration.

```csharp
public VoiceNextConfiguration(VoiceNextConfiguration other)
```

#### Parameters

`other` [VoiceNextConfiguration](DSharpPlus.VoiceNext.VoiceNextConfiguration.md)

Configuration the properties of which are to be copied.

## Properties

### <a id="DSharpPlus_VoiceNext_VoiceNextConfiguration_AudioFormat"></a>AudioFormat

<p>Sets the audio format for Opus. This will determine the quality of the audio output.</p>
<p>Defaults to <xref href="DSharpPlus.VoiceNext.AudioFormat.Default" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public AudioFormat AudioFormat { set; }
```

#### Property Value

[AudioFormat](DSharpPlus.VoiceNext.AudioFormat.md)

### <a id="DSharpPlus_VoiceNext_VoiceNextConfiguration_EnableIncoming"></a>EnableIncoming

<p>Sets whether incoming voice receiver should be enabled.</p>
<p>Defaults to false.</p>

```csharp
public bool EnableIncoming { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_VoiceNext_VoiceNextConfiguration_PacketQueueSize"></a>PacketQueueSize

<p>Sets the size of the packet queue.</p>
<p>Defaults to 25 or ~500ms.</p>

```csharp
public int PacketQueueSize { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

