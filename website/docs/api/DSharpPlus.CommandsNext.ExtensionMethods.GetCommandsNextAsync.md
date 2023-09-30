# Method GetCommandsNextAsync

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_GetCommandsNextAsync_DSharpPlus_DiscordShardedClient_"></a>GetCommandsNextAsync\(DiscordShardedClient\)

Gets the active CommandsNext modules for all shards in this client.

```csharp
public static Task<IReadOnlyDictionary<int, CommandsNextExtension>> GetCommandsNextAsync(this DiscordShardedClient client)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Client to get CommandsNext instances from.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>\>

A dictionary of the modules, indexed by shard id.

