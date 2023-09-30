# Enum GatewayOpCode

Namespace: [DSharpPlus.Net.Abstractions](DSharpPlus.Net.Abstractions.md)  
Assembly: DSharpPlus.dll

Specifies an OP code in a gateway payload.

```csharp
public enum GatewayOpCode
```

###### Extension Methods

[ExtensionMethods.GetName<GatewayOpCode\>\(GatewayOpCode\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Dispatch = 0` 

Used for dispatching events.

`GuildSync = 12` 

Used to request guild synchronization.

`Heartbeat = 1` 

Used for pinging the gateway or client, to ensure the connection is still alive.

`HeartbeatAck = 11` 

Used to acknowledge a heartbeat.

`Hello = 10` 

Used by the gateway upon connecting.

`Identify = 2` 

Used for initial handshake with the gateway.

`InvalidSession = 9` 

Used to notify the client about an invalidated session.

`Reconnect = 7` 

Used to notify the client that it has to reconnect.

`RequestGuildMembers = 8` 

Used to request guild members.

`Resume = 6` 

Used to resume a closed connection.

`StatusUpdate = 3` 

Used to update client status.

`VoiceServerPing = 5` 

Used for pinging the voice gateway or client, to ensure the connection is still alive.

`VoiceStateUpdate = 4` 

Used to update voice state, when joining, leaving, or moving between voice channels.

