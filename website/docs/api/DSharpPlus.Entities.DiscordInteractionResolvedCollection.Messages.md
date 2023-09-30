# Property Messages

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordInteractionResolvedCollection_Messages"></a>Messages

Gets the resolved message objects, if any.

```csharp
[JsonProperty("messages", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyDictionary<ulong, DiscordMessage> Messages { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

