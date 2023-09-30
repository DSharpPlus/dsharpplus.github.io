# Property Channels

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_Channels"></a>Channels

Gets a dictionary of all the channels associated with this guild. The dictionary's key is the channel ID.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordChannel> Channels { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

