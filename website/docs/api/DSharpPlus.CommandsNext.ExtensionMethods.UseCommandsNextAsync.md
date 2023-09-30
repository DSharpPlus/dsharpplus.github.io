# Method UseCommandsNextAsync

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_UseCommandsNextAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_CommandsNext_CommandsNextConfiguration_"></a>UseCommandsNextAsync\(DiscordShardedClient, CommandsNextConfiguration\)

Enables CommandsNext module on all shards in this <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static Task<IReadOnlyDictionary<int, CommandsNextExtension>> UseCommandsNextAsync(this DiscordShardedClient client, CommandsNextConfiguration cfg)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Client to enable CommandsNext for.

`cfg` [CommandsNextConfiguration](DSharpPlus.CommandsNext.CommandsNextConfiguration.md)

CommandsNext configuration to use.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>\>

A dictionary of created <xref href="DSharpPlus.CommandsNext.CommandsNextExtension" data-throw-if-not-resolved="false"></xref>, indexed by shard id.

