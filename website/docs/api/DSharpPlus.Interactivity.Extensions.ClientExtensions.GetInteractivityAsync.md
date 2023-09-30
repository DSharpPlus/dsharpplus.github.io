# Method GetInteractivityAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_GetInteractivityAsync_DSharpPlus_DiscordShardedClient_"></a>GetInteractivityAsync\(DiscordShardedClient\)

Retrieves a <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance for each shard.

```csharp
public static Task<ReadOnlyDictionary<int, InteractivityExtension>> GetInteractivityAsync(this DiscordShardedClient client)
```

### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to retrieve interactivity instances from.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)\>\>

A dictionary containing <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

