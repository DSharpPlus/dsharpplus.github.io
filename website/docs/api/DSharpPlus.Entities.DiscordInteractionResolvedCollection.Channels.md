# Property Channels

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Channels"></a>Channels

Gets the resolved channel objects, if any.

```csharp
[JsonProperty("channels", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordChannel> Channels { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

