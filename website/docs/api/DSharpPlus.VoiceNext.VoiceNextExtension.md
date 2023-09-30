# Class VoiceNextExtension

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

Represents VoiceNext extension, which acts as Discord voice client.

```csharp
public sealed class VoiceNextExtension : BaseExtension
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseExtension](DSharpPlus.BaseExtension.md) ← 
[VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)

###### Inherited Members

[BaseExtension.Client](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Client), 
[BaseExtension.Dispose\(\)](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Dispose)

## Properties

### <a id="DSharpPlus_VoiceNext_VoiceNextExtension_IsIncomingEnabled"></a>IsIncomingEnabled

Gets whether this connection has incoming voice enabled.

```csharp
public bool IsIncomingEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="DSharpPlus_VoiceNext_VoiceNextExtension_ConnectAsync_DSharpPlus_Entities_DiscordChannel_"></a>ConnectAsync\(DiscordChannel\)

Create a VoiceNext connection for the specified channel.

```csharp
public Task<VoiceNextConnection> ConnectAsync(DiscordChannel channel)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to connect to.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md)\>

VoiceNext connection for this channel.

### <a id="DSharpPlus_VoiceNext_VoiceNextExtension_Dispose"></a>Dispose\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

```csharp
public override void Dispose()
```

### <a id="DSharpPlus_VoiceNext_VoiceNextExtension_GetConnection_DSharpPlus_Entities_DiscordGuild_"></a>GetConnection\(DiscordGuild\)

Gets a VoiceNext connection for specified guild.

```csharp
public VoiceNextConnection GetConnection(DiscordGuild guild)
```

#### Parameters

`guild` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

Guild to get VoiceNext connection for.

#### Returns

[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md)

VoiceNext connection for the specified guild.

### <a id="DSharpPlus_VoiceNext_VoiceNextExtension_Setup_DSharpPlus_DiscordClient_"></a>Setup\(DiscordClient\)

DO NOT USE THIS MANUALLY.

```csharp
protected override void Setup(DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

DO NOT USE THIS MANUALLY.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

