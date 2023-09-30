# Method GetAssetsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordApplication_GetAssetsAsync_System_Boolean_"></a>GetAssetsAsync\(bool\)

Retrieves this application's assets.

```csharp
public Task<IReadOnlyList<DiscordApplicationAsset>> GetAssetsAsync(bool updateCache = false)
```

### Parameters

`updateCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request and update the cached assets.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)\>\>

This application's assets.

