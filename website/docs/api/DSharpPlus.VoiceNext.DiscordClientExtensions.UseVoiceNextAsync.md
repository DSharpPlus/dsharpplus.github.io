# Method UseVoiceNextAsync

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_UseVoiceNextAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_VoiceNext_VoiceNextConfiguration_"></a>UseVoiceNextAsync\(DiscordShardedClient, VoiceNextConfiguration\)

Creates new VoiceNext clients on all shards in a given sharded client.

```csharp
public static Task<IReadOnlyDictionary<int, VoiceNextExtension>> UseVoiceNextAsync(this DiscordShardedClient client, VoiceNextConfiguration config)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Discord sharded client to create VoiceNext instances for.

`config` [VoiceNextConfiguration](DSharpPlus.VoiceNext.VoiceNextConfiguration.md)

Configuration for the VoiceNext clients.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)\>\>

A dictionary of created VoiceNext clients.

