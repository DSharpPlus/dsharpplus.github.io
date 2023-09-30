# Class SocketBinaryMessageEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for binary message websocket event.

```csharp
public sealed class SocketBinaryMessageEventArgs : SocketMessageEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[SocketMessageEventArgs](DSharpPlus.EventArgs.SocketMessageEventArgs.md) ← 
[SocketBinaryMessageEventArgs](DSharpPlus.EventArgs.SocketBinaryMessageEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Constructors

### <a id="DSharpPlus_EventArgs_SocketBinaryMessageEventArgs__ctor_System_Byte___"></a>SocketBinaryMessageEventArgs\(byte\[\]\)

Creates a new instance of binary message event arguments.

```csharp
public SocketBinaryMessageEventArgs(byte[] message)
```

#### Parameters

`message` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

Received message bytes.

## Properties

### <a id="DSharpPlus_EventArgs_SocketBinaryMessageEventArgs_Message"></a>Message

Gets the received message bytes.

```csharp
public byte[] Message { get; }
```

#### Property Value

[byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

