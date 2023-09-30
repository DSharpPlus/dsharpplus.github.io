# Class SocketTextMessageEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for text message websocket event.

```csharp
public sealed class SocketTextMessageEventArgs : SocketMessageEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[SocketMessageEventArgs](DSharpPlus.EventArgs.SocketMessageEventArgs.md) ← 
[SocketTextMessageEventArgs](DSharpPlus.EventArgs.SocketTextMessageEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Constructors

### <a id="DSharpPlus_EventArgs_SocketTextMessageEventArgs__ctor_System_String_"></a>SocketTextMessageEventArgs\(string\)

Creates a new instance of text message event arguments.

```csharp
public SocketTextMessageEventArgs(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

Received message string.

## Properties

### <a id="DSharpPlus_EventArgs_SocketTextMessageEventArgs_Message"></a>Message

Gets the received message string.

```csharp
public string Message { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

