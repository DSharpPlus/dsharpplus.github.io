# Property Threads

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_Threads"></a>Threads

Gets a dictionary of all the active threads associated with this guild the user has permission to view. The dictionary's key is the channel ID.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordThreadChannel> Threads { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

