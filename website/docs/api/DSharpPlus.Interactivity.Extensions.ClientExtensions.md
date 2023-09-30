# Class ClientExtensions

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

Interactivity extension methods for <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static class ClientExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ClientExtensions](DSharpPlus.Interactivity.Extensions.ClientExtensions.md)

## Methods

### <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_GetInteractivity_DSharpPlus_DiscordClient_"></a>GetInteractivity\(DiscordClient\)

Retrieves the registered <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance for this client.

```csharp
public static InteractivityExtension GetInteractivity(this DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

The client to retrieve an <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance from.

#### Returns

[InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)

An existing <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance, or <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> if interactivity is not enabled for the <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> instance.

### <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_GetInteractivityAsync_DSharpPlus_DiscordShardedClient_"></a>GetInteractivityAsync\(DiscordShardedClient\)

Retrieves a <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance for each shard.

```csharp
public static Task<ReadOnlyDictionary<int, InteractivityExtension>> GetInteractivityAsync(this DiscordShardedClient client)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to retrieve interactivity instances from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)\>\>

A dictionary containing <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

### <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_UseInteractivity_DSharpPlus_DiscordClient_DSharpPlus_Interactivity_InteractivityConfiguration_"></a>UseInteractivity\(DiscordClient, InteractivityConfiguration\)

Enables interactivity for this <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> instance.

```csharp
public static InteractivityExtension UseInteractivity(this DiscordClient client, InteractivityConfiguration configuration = null)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

The client to enable interactivity for.

`configuration` [InteractivityConfiguration](DSharpPlus.Interactivity.InteractivityConfiguration.md)

A configuration instance. Default configuration values will be used if none is provided.

#### Returns

[InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)

A brand new <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instance.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity has already been enabled for the client instance.

### <a id="DSharpPlus_Interactivity_Extensions_ClientExtensions_UseInteractivityAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_Interactivity_InteractivityConfiguration_"></a>UseInteractivityAsync\(DiscordShardedClient, InteractivityConfiguration\)

Enables interactivity for each shard.

```csharp
public static Task<IReadOnlyDictionary<int, InteractivityExtension>> UseInteractivityAsync(this DiscordShardedClient client, InteractivityConfiguration configuration = null)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

The shard client to enable interactivity for.

`configuration` [InteractivityConfiguration](DSharpPlus.Interactivity.InteractivityConfiguration.md)

Configuration to use for all shards. If one isn't provided, default configuration values will be used.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)\>\>

A dictionary containing new <xref href="DSharpPlus.Interactivity.InteractivityExtension" data-throw-if-not-resolved="false"></xref> instances for each shard.

