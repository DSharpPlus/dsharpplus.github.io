# Class DiscordClientExtensions

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

```csharp
public static class DiscordClientExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordClientExtensions](DSharpPlus.VoiceNext.DiscordClientExtensions.md)

## Methods

### <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_ConnectAsync_DSharpPlus_Entities_DiscordChannel_"></a>ConnectAsync\(DiscordChannel\)

Connects to this voice channel using VoiceNext.

```csharp
public static Task<VoiceNextConnection> ConnectAsync(this DiscordChannel channel)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to connect to.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md)\>

If successful, the VoiceNext connection.

### <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_GetVoiceNext_DSharpPlus_DiscordClient_"></a>GetVoiceNext\(DiscordClient\)

Gets the active instance of VoiceNext client for the DiscordClient.

```csharp
public static VoiceNextExtension GetVoiceNext(this DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Discord client to get VoiceNext instance for.

#### Returns

[VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)

VoiceNext client instance.

### <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_GetVoiceNextAsync_DSharpPlus_DiscordShardedClient_"></a>GetVoiceNextAsync\(DiscordShardedClient\)

Retrieves a <xref href="DSharpPlus.VoiceNext.VoiceNextExtension" data-throw-if-not-resolved="false"></xref> instance for each shard.

```csharp
public static Task<IReadOnlyDictionary<int, VoiceNextExtension>> GetVoiceNextAsync(this DiscordShardedClient client)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to retrieve <xref href="DSharpPlus.VoiceNext.VoiceNextExtension" data-throw-if-not-resolved="false"></xref> instances from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)\>\>

A dictionary containing <xref href="DSharpPlus.VoiceNext.VoiceNextExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

### <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_UseVoiceNext_DSharpPlus_DiscordClient_"></a>UseVoiceNext\(DiscordClient\)

Creates a new VoiceNext client with default settings.

```csharp
public static VoiceNextExtension UseVoiceNext(this DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Discord client to create VoiceNext instance for.

#### Returns

[VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)

VoiceNext client instance.

### <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_UseVoiceNext_DSharpPlus_DiscordClient_DSharpPlus_VoiceNext_VoiceNextConfiguration_"></a>UseVoiceNext\(DiscordClient, VoiceNextConfiguration\)

Creates a new VoiceNext client with specified settings.

```csharp
public static VoiceNextExtension UseVoiceNext(this DiscordClient client, VoiceNextConfiguration config)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Discord client to create VoiceNext instance for.

`config` [VoiceNextConfiguration](DSharpPlus.VoiceNext.VoiceNextConfiguration.md)

Configuration for the VoiceNext client.

#### Returns

[VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)

VoiceNext client instance.

### <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_UseVoiceNextAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_VoiceNext_VoiceNextConfiguration_"></a>UseVoiceNextAsync\(DiscordShardedClient, VoiceNextConfiguration\)

Creates new VoiceNext clients on all shards in a given sharded client.

```csharp
public static Task<IReadOnlyDictionary<int, VoiceNextExtension>> UseVoiceNextAsync(this DiscordShardedClient client, VoiceNextConfiguration config)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Discord sharded client to create VoiceNext instances for.

`config` [VoiceNextConfiguration](DSharpPlus.VoiceNext.VoiceNextConfiguration.md)

Configuration for the VoiceNext clients.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)\>\>

A dictionary of created VoiceNext clients.

