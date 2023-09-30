# Property Roles

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Roles"></a>Roles

Gets the resolved role objects, if any.

```csharp
[JsonProperty("roles", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordRole> Roles { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

