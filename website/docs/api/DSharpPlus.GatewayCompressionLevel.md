# Enum GatewayCompressionLevel

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Determines at which level should the WebSocket traffic be compressed.

```csharp
public enum GatewayCompressionLevel : byte
```

###### Extension Methods

[ExtensionMethods.GetName<GatewayCompressionLevel\>\(GatewayCompressionLevel\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`None = 0` 

Defines that traffic should not be compressed at all.

`Payload = 1` 

Defines that traffic should be compressed at payload level.

`Stream = 2` 

Defines that entire traffic stream should be compressed.

