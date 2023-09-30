# Method UseLavalinkAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_DiscordClientExtensions_UseLavalinkAsync_DSharpPlus_DiscordShardedClient_"></a>UseLavalinkAsync\(DiscordShardedClient\)

Creates new Lavalink clients on all shards in a given sharded client.

```csharp
public static Task<IReadOnlyDictionary<int, LavalinkExtension>> UseLavalinkAsync(this DiscordShardedClient client)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Discord sharded client to create Lavalink instances for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)\>\>

A dictionary of created Lavalink clients.

