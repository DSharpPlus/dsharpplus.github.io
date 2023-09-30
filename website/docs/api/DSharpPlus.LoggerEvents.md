# Class LoggerEvents

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Contains well-defined event IDs used by core of DSharpPlus.

```csharp
public static class LoggerEvents
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LoggerEvents](DSharpPlus.LoggerEvents.md)

## Properties

### <a id="DSharpPlus_LoggerEvents_AuditLog"></a>AuditLog

Events pertaining to audit log processing.

```csharp
public static EventId AuditLog { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_ConnectionClose"></a>ConnectionClose

Events pertaining to clean connection closes.

```csharp
public static EventId ConnectionClose { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_ConnectionFailure"></a>ConnectionFailure

Events typically emitted whenever WebSocket connections fail or are terminated.

```csharp
public static EventId ConnectionFailure { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_EventHandlerException"></a>EventHandlerException

Events emitted when exceptions are thrown in handlers attached to async events.

```csharp
public static EventId EventHandlerException { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_GatewayWsRx"></a>GatewayWsRx

Events containing raw (but decompressed) payloads, received from Discord Gateway.

```csharp
public static EventId GatewayWsRx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_GatewayWsTx"></a>GatewayWsTx

Events containing raw payloads, as they're being sent to Discord Gateway.

```csharp
public static EventId GatewayWsTx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_Heartbeat"></a>Heartbeat

Events pertaining to connection lifecycle, specifically, heartbeats.

```csharp
public static EventId Heartbeat { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_HeartbeatFailure"></a>HeartbeatFailure

Events pertaining to various heartbeat failures, typically fatal.

```csharp
public static EventId HeartbeatFailure { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_Intents"></a>Intents

Events pertaining to Gateway Intents. Typically diagnostic information.

```csharp
public static EventId Intents { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_Misc"></a>Misc

Miscellaneous events, that do not fit in any other category.

```csharp
public static EventId Misc { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RatelimitDiag"></a>RatelimitDiag

Events pertaining to ratelimit diagnostics. Typically contain raw bucket info.

```csharp
public static EventId RatelimitDiag { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RatelimitHit"></a>RatelimitHit

Events pertaining to ratelimit exhaustion.

```csharp
public static EventId RatelimitHit { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RatelimitPreemptive"></a>RatelimitPreemptive

Events emitted when a ratelimit is exhausted and a request is preemtively blocked.

```csharp
public static EventId RatelimitPreemptive { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RestCleaner"></a>RestCleaner

```csharp
public static EventId RestCleaner { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RestError"></a>RestError

Events emitted when REST processing fails for any reason.

```csharp
public static EventId RestError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RestHashMover"></a>RestHashMover

```csharp
public static EventId RestHashMover { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RestRx"></a>RestRx

Events containing raw payloads, as they're received from Discord's REST API.

```csharp
public static EventId RestRx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_RestTx"></a>RestTx

Events containing raw payloads, as they're sent to Discord's REST API.

```csharp
public static EventId RestTx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_SessionUpdate"></a>SessionUpdate

Events pertaining to Discord-issued session state updates.

```csharp
public static EventId SessionUpdate { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_ShardClientError"></a>ShardClientError

Events pertaining to the <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>'s shards not initializing correctly.

```csharp
public static EventId ShardClientError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_ShardRest"></a>ShardRest

Events pertaining to Discord API requests from the <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static EventId ShardRest { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_ShardShutdown"></a>ShardShutdown

Events pertaining to autosharded client shard shutdown, clean or otherwise.

```csharp
public static EventId ShardShutdown { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_ShardStartup"></a>ShardStartup

Events pertaining to the <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref> shard startup.

```csharp
public static EventId ShardStartup { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_Startup"></a>Startup

Events pertaining to startup tasks.

```csharp
public static EventId Startup { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_WebSocketReceive"></a>WebSocketReceive

Events emitted for various high-level WebSocket receive events.

```csharp
public static EventId WebSocketReceive { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_WebSocketReceiveFailure"></a>WebSocketReceiveFailure

Events emitted for various WebSocket payload processing failures, typically when deserialization or decoding fails.

```csharp
public static EventId WebSocketReceiveFailure { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_WebSocketReceiveRaw"></a>WebSocketReceiveRaw

Events emitted for various low-level WebSocket receive events.

```csharp
public static EventId WebSocketReceiveRaw { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_LoggerEvents_WebSocketSendRaw"></a>WebSocketSendRaw

Events emitted for various low-level WebSocket send events.

```csharp
public static EventId WebSocketSendRaw { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

