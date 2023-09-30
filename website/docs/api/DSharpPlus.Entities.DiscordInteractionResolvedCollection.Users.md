# Property Users

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Users"></a>Users

Gets the resolved user objects, if any.

```csharp
[JsonProperty("users", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordUser> Users { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

