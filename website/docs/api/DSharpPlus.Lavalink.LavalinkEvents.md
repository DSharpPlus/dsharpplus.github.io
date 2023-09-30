# Class LavalinkEvents

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Contains well-defined event IDs used by the Lavalink extension.

```csharp
public static class LavalinkEvents
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkEvents](DSharpPlus.Lavalink.LavalinkEvents.md)

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkEvents_Intents"></a>Intents

Events pertaining to Gateway Intents. Typically diagnostic information.

```csharp
public static EventId Intents { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_LavalinkConnected"></a>LavalinkConnected

Events emitted for successful connections made to Lavalink.

```csharp
public static EventId LavalinkConnected { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_LavalinkConnectionClosed"></a>LavalinkConnectionClosed

Events emitted for clean disconnects from Lavalink.

```csharp
public static EventId LavalinkConnectionClosed { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_LavalinkConnectionError"></a>LavalinkConnectionError

Events pertaining to Lavalink node connection errors.

```csharp
public static EventId LavalinkConnectionError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_LavalinkDecodeError"></a>LavalinkDecodeError

Events pertaining to errors that occur when decoding payloads received from Lavalink nodes.

```csharp
public static EventId LavalinkDecodeError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_LavalinkRestError"></a>LavalinkRestError

Events emitted when Lavalink's REST API responds with an error.

```csharp
public static EventId LavalinkRestError { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_LavalinkWsRx"></a>LavalinkWsRx

Events containing raw payloads, received from Lavalink nodes.

```csharp
public static EventId LavalinkWsRx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_LavalinkWsTx"></a>LavalinkWsTx

Events containing raw payloads, as they're being sent to Lavalink nodes.

```csharp
public static EventId LavalinkWsTx { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

### <a id="DSharpPlus_Lavalink_LavalinkEvents_Misc"></a>Misc

Miscellaneous events, that do not fit in any other category.

```csharp
public static EventId Misc { get; }
```

#### Property Value

[EventId](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.eventid)

