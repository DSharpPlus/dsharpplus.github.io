# Class DiscordClientExtensions

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

```csharp
public static class DiscordClientExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordClientExtensions](DSharpPlus.Lavalink.DiscordClientExtensions.md)

## Methods

### <a id="DSharpPlus_Lavalink_DiscordClientExtensions_ConnectAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Lavalink_LavalinkNodeConnection_"></a>ConnectAsync\(DiscordChannel, LavalinkNodeConnection\)

Connects to this voice channel using Lavalink.

```csharp
public static Task ConnectAsync(this DiscordChannel channel, LavalinkNodeConnection node)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to connect to.

`node` [LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

Lavalink node to connect through.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

If successful, the Lavalink client.

### <a id="DSharpPlus_Lavalink_DiscordClientExtensions_GetLavalink_DSharpPlus_DiscordClient_"></a>GetLavalink\(DiscordClient\)

Gets the active instance of the Lavalink client for the DiscordClient.

```csharp
public static LavalinkExtension GetLavalink(this DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Discord client to get Lavalink instance for.

#### Returns

[LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)

Lavalink client instance.

### <a id="DSharpPlus_Lavalink_DiscordClientExtensions_GetLavalinkAsync_DSharpPlus_DiscordShardedClient_"></a>GetLavalinkAsync\(DiscordShardedClient\)

Retrieves a <xref href="DSharpPlus.Lavalink.LavalinkExtension" data-throw-if-not-resolved="false"></xref> instance for each shard.

```csharp
public static Task<IReadOnlyDictionary<int, LavalinkExtension>> GetLavalinkAsync(this DiscordShardedClient client)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to retrieve <xref href="DSharpPlus.Lavalink.LavalinkExtension" data-throw-if-not-resolved="false"></xref> instances from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)\>\>

A dictionary containing <xref href="DSharpPlus.Lavalink.LavalinkExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

### <a id="DSharpPlus_Lavalink_DiscordClientExtensions_UseLavalink_DSharpPlus_DiscordClient_"></a>UseLavalink\(DiscordClient\)

Creates a new Lavalink client with specified settings.

```csharp
public static LavalinkExtension UseLavalink(this DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Discord client to create Lavalink instance for.

#### Returns

[LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)

Lavalink client instance.

### <a id="DSharpPlus_Lavalink_DiscordClientExtensions_UseLavalinkAsync_DSharpPlus_DiscordShardedClient_"></a>UseLavalinkAsync\(DiscordShardedClient\)

Creates new Lavalink clients on all shards in a given sharded client.

```csharp
public static Task<IReadOnlyDictionary<int, LavalinkExtension>> UseLavalinkAsync(this DiscordShardedClient client)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Discord sharded client to create Lavalink instances for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)\>\>

A dictionary of created Lavalink clients.

