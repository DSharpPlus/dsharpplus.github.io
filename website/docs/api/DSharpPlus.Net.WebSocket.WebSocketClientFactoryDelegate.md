# Delegate WebSocketClientFactoryDelegate

Namespace: [DSharpPlus.Net.WebSocket](DSharpPlus.Net.WebSocket.md)  
Assembly: DSharpPlus.dll

Creates an instance of a WebSocket client implementation.

```csharp
public delegate IWebSocketClient WebSocketClientFactoryDelegate(IWebProxy proxy)
```

#### Parameters

`proxy` [IWebProxy](https://learn.microsoft.com/dotnet/api/system.net.iwebproxy)

Proxy settings to use for the new WebSocket client instance.

#### Returns

[IWebSocketClient](DSharpPlus.Net.WebSocket.IWebSocketClient.md)

Constructed WebSocket client implementation.

