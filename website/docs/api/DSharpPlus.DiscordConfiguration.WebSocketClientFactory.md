# Property WebSocketClientFactory

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordConfiguration_WebSocketClientFactory"></a>WebSocketClientFactory

<p>Sets the factory method used to create instances of WebSocket clients.</p>
<p>Use <xref href="DSharpPlus.Net.WebSocket.WebSocketClient.CreateNew(System.Net.IWebProxy)" data-throw-if-not-resolved="false"></xref> and equivalents on other implementations to switch out client implementations.</p>
<p>Defaults to <xref href="DSharpPlus.Net.WebSocket.WebSocketClient.CreateNew(System.Net.IWebProxy)" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public WebSocketClientFactoryDelegate WebSocketClientFactory { set; }
```

### Property Value

[WebSocketClientFactoryDelegate](DSharpPlus.Net.WebSocket.WebSocketClientFactoryDelegate.md)

