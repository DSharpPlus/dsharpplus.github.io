# Class GatewayInfo

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

Represents information used to identify with Discord.

```csharp
public sealed class GatewayInfo
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[GatewayInfo](DSharpPlus.Net.GatewayInfo.md)

## Properties

### <a id="DSharpPlus_Net_GatewayInfo_SessionBucket"></a>SessionBucket

Gets the session start limit data.

```csharp
[JsonProperty("session_start_limit")]
public SessionBucket SessionBucket { get; }
```

#### Property Value

[SessionBucket](DSharpPlus.Net.SessionBucket.md)

### <a id="DSharpPlus_Net_GatewayInfo_ShardCount"></a>ShardCount

Gets the recommended amount of shards.

```csharp
[JsonProperty("shards")]
public int ShardCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Net_GatewayInfo_Url"></a>Url

Gets the gateway URL for the WebSocket connection.

```csharp
[JsonProperty("url")]
public string Url { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

