# Property GatewayCompressionLevel

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordConfiguration_GatewayCompressionLevel"></a>GatewayCompressionLevel

<p>Sets the level of compression for WebSocket traffic.</p>
<p>Disabling this option will increase the amount of traffic sent via WebSocket. Setting <xref href="DSharpPlus.GatewayCompressionLevel.Payload" data-throw-if-not-resolved="false"></xref> will enable compression for READY and GUILD_CREATE payloads. Setting <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> will enable compression for the entire WebSocket stream, drastically reducing amount of traffic.</p>
<p>Defaults to <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public GatewayCompressionLevel GatewayCompressionLevel { set; }
```

### Property Value

[GatewayCompressionLevel](DSharpPlus.GatewayCompressionLevel.md)

