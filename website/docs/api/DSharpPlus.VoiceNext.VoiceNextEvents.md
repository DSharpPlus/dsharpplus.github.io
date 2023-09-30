# Class VoiceNextEvents

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

Contains well-defined event IDs used by the VoiceNext extension.

```csharp
public static class VoiceNextEvents
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[VoiceNextEvents](DSharpPlus.VoiceNext.VoiceNextEvents.md)

## Properties

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_Misc"></a>Misc

Miscellaneous events, that do not fit in any other category.

```csharp
public static EventId Misc { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceConnectionClose"></a>VoiceConnectionClose

Events emitted for Voice Gateway connection closes, clean or otherwise.

```csharp
public static EventId VoiceConnectionClose { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceDispatch"></a>VoiceDispatch

Events emitted for high-level dispatch receive events.

```csharp
public static EventId VoiceDispatch { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceGatewayError"></a>VoiceGatewayError

Events emitted when decoding data received via Voice Gateway fails for any reason.

```csharp
public static EventId VoiceGatewayError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceHandshake"></a>VoiceHandshake

Events pertaining to Voice Gateway connection early lifespan, specifically, the establishing thereof as well as negotiating various modes.

```csharp
public static EventId VoiceHandshake { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceHeartbeat"></a>VoiceHeartbeat

Events pertaining to Voice Gateway connection lifespan, specifically, heartbeats.

```csharp
public static EventId VoiceHeartbeat { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceKeepalive"></a>VoiceKeepalive

Events pertaining to UDP connection lifespan, specifically the keepalive (or heartbeats).

```csharp
public static EventId VoiceKeepalive { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceReceiveFailure"></a>VoiceReceiveFailure

Events emitted when incoming voice data is corrupted, or packets are being dropped.

```csharp
public static EventId VoiceReceiveFailure { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceWsRx"></a>VoiceWsRx

Events containing raw (but decompressed) payloads, received from Discord Voice Gateway.

```csharp
public static EventId VoiceWsRx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_VoiceNext_VoiceNextEvents_VoiceWsTx"></a>VoiceWsTx

Events containing raw payloads, as they're being sent to Discord Voice Gateway.

```csharp
public static EventId VoiceWsTx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

