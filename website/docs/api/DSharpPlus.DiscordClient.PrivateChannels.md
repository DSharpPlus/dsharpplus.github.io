# Property PrivateChannels

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_PrivateChannels"></a>PrivateChannels

Gets a dictionary of DM channels that have been cached by this client. The dictionary's key is the channel
ID.

```csharp
public IReadOnlyDictionary<ulong, DiscordDmChannel> PrivateChannels { get; }
```

### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

