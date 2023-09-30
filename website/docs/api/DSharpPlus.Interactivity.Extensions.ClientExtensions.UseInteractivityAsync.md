# Method UseInteractivityAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_UseInteractivityAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_Interactivity_InteractivityConfiguration_"></a>UseInteractivityAsync\(DiscordShardedClient, InteractivityConfiguration\)

Enables interactivity for each shard.

```csharp
public static Task<IReadOnlyDictionary<int, InteractivityExtension>> UseInteractivityAsync(this DiscordShardedClient client, InteractivityConfiguration configuration = null)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to enable interactivity for.

`configuration` [InteractivityConfiguration](DSharpPlus.Interactivity.InteractivityConfiguration.md)

Configuration to use for all shards. If one isn't provided, default configuration values will be used.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)\>\>

A dictionary containing new <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

