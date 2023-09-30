# Method UseSlashCommandsAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_ExtensionMethods_UseSlashCommandsAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_SlashCommands_SlashCommandsConfiguration_"></a>UseSlashCommandsAsync\(DiscordShardedClient, SlashCommandsConfiguration\)

Enables slash commands on this <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static Task<IReadOnlyDictionary<int, SlashCommandsExtension>> UseSlashCommandsAsync(this DiscordShardedClient client, SlashCommandsConfiguration config = null)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Client to enable slash commands on.

`config` [SlashCommandsConfiguration](DSharpPlus.SlashCommands.SlashCommandsConfiguration.md)

Configuration to use.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)\>\>

A dictionary of created <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension" data-throw-if-not-resolved="false"></xref> with the key being the shard id.

