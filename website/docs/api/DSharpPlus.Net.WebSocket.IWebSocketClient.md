# Interface IWebSocketClient

Namespace: [DSharpPlus.Net.WebSocket](DSharpPlus.Net.WebSocket.md)  
Assembly: DSharpPlus.dll

Represents a base abstraction for all WebSocket client implementations.

```csharp
public interface IWebSocketClient
```

## Properties

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_DefaultHeaders"></a>DefaultHeaders

Gets the collection of default headers to send when connecting to the remote endpoint.

```csharp
IReadOnlyDictionary<string, string> DefaultHeaders { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_Proxy"></a>Proxy

Gets the proxy settings for this client.

```csharp
IWebProxy Proxy { get; }
```

#### Property Value

[IWebProxy](https://learn.microsoft.com/dotnet/api/system.net.iwebproxy)

## Methods

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_AddDefaultHeader_System_String_System_String_"></a>AddDefaultHeader\(string, string\)

Adds a header to the default header collection.

```csharp
bool AddDefaultHeader(string name, string value)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the header to add.

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Value of the header to add.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation succeeded.

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_ConnectAsync_System_Uri_"></a>ConnectAsync\(Uri\)

Connects to a specified remote WebSocket endpoint.

```csharp
Task ConnectAsync(Uri uri)
```

#### Parameters

`uri` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

The URI of the WebSocket endpoint.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_DisconnectAsync_System_Int32_System_String_"></a>DisconnectAsync\(int, string\)

Disconnects the WebSocket connection.

```csharp
Task DisconnectAsync(int code = 1000, string message = "")
```

#### Parameters

`code` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_RemoveDefaultHeader_System_String_"></a>RemoveDefaultHeader\(string\)

Removes a header from the default header collection.

```csharp
bool RemoveDefaultHeader(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the header to remove.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the operation succeeded.

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_SendMessageAsync_System_String_"></a>SendMessageAsync\(string\)

Send a message to the WebSocket server.

```csharp
Task SendMessageAsync(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

The message to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_Connected"></a>Connected

Triggered when the client connects successfully.

```csharp
event AsyncEventHandler<IWebSocketClient, SocketEventArgs> Connected
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[IWebSocketClient](DSharpPlus.Net.WebSocket.IWebSocketClient.md), [SocketEventArgs](DSharpPlus.EventArgs.SocketEventArgs.md)\>

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_Disconnected"></a>Disconnected

Triggered when the client is disconnected.

```csharp
event AsyncEventHandler<IWebSocketClient, SocketCloseEventArgs> Disconnected
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[IWebSocketClient](DSharpPlus.Net.WebSocket.IWebSocketClient.md), [SocketCloseEventArgs](DSharpPlus.EventArgs.SocketCloseEventArgs.md)\>

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_ExceptionThrown"></a>ExceptionThrown

Triggered when an error occurs in the client.

```csharp
event AsyncEventHandler<IWebSocketClient, SocketErrorEventArgs> ExceptionThrown
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[IWebSocketClient](DSharpPlus.Net.WebSocket.IWebSocketClient.md), [SocketErrorEventArgs](DSharpPlus.EventArgs.SocketErrorEventArgs.md)\>

### <a id="DSharpPlus_Net_WebSocket_IWebSocketClient_MessageReceived"></a>MessageReceived

Triggered when the client receives a message from the remote party.

```csharp
event AsyncEventHandler<IWebSocketClient, SocketMessageEventArgs> MessageReceived
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[IWebSocketClient](DSharpPlus.Net.WebSocket.IWebSocketClient.md), [SocketMessageEventArgs](DSharpPlus.EventArgs.SocketMessageEventArgs.md)\>

