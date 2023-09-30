# Method GetVoiceNextAsync

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_GetVoiceNextAsync_DSharpPlus_DiscordShardedClient_"></a>GetVoiceNextAsync\(DiscordShardedClient\)

Retrieves a <xref href="DSharpPlus.VoiceNext.VoiceNextExtension" data-throw-if-not-resolved="false"></xref> instance for each shard.

```csharp
public static Task<IReadOnlyDictionary<int, VoiceNextExtension>> GetVoiceNextAsync(this DiscordShardedClient client)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to retrieve <xref href="DSharpPlus.VoiceNext.VoiceNextExtension" data-throw-if-not-resolved="false"></xref> instances from.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [VoiceNextExtension](DSharpPlus.VoiceNext.VoiceNextExtension.md)\>\>

A dictionary containing <xref href="DSharpPlus.VoiceNext.VoiceNextExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

