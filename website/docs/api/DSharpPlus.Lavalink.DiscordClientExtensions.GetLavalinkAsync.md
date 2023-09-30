# Method GetLavalinkAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_DiscordClientExtensions_GetLavalinkAsync_DSharpPlus_DiscordShardedClient_"></a>GetLavalinkAsync\(DiscordShardedClient\)

Retrieves a <xref href="DSharpPlus.Lavalink.LavalinkExtension" data-throw-if-not-resolved="false"></xref> instance for each shard.

```csharp
public static Task<IReadOnlyDictionary<int, LavalinkExtension>> GetLavalinkAsync(this DiscordShardedClient client)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to retrieve <xref href="DSharpPlus.Lavalink.LavalinkExtension" data-throw-if-not-resolved="false"></xref> instances from.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)\>\>

A dictionary containing <xref href="DSharpPlus.Lavalink.LavalinkExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

