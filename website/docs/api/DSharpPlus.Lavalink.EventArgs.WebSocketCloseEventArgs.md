# Class WebSocketCloseEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents arguments for <xref href="DSharpPlus.Lavalink.LavalinkGuildConnection.DiscordWebSocketClosed" data-throw-if-not-resolved="false"></xref> event.

```csharp
public sealed class WebSocketCloseEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[WebSocketCloseEventArgs](DSharpPlus.Lavalink.EventArgs.WebSocketCloseEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_WebSocketCloseEventArgs_Code"></a>Code

Gets the WebSocket close code.

```csharp
public int Code { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_EventArgs_WebSocketCloseEventArgs_Reason"></a>Reason

Gets the WebSocket close reason.

```csharp
public string Reason { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_EventArgs_WebSocketCloseEventArgs_Remote"></a>Remote

Gets whether the termination was initiated by the remote party (i.e. Discord).

```csharp
public bool Remote { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

