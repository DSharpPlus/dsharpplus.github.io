# Property BlockIndex

Namespace: [DSharpPlus.Lavalink.Entities](DSharpPlus.Lavalink.Entities.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_Entities_LavalinkRouteStatusDetails_BlockIndex"></a>BlockIndex

Gets the information in which /64 block ips are chosen. This number increases on each ban.
<p>Only present in the <xref href="DSharpPlus.Lavalink.LavalinkRoutePlannerType.RotatingNanoIpRoutePlanner" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("blockIndex", NullValueHandling = NullValueHandling.Ignore)]
public string BlockIndex { get; }
```

### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

