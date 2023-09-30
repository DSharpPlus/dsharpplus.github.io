# Class SocketErrorEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.SocketErrored" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class SocketErrorEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[SocketErrorEventArgs](DSharpPlus.EventArgs.SocketErrorEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Constructors

### <a id="DSharpPlus_EventArgs_SocketErrorEventArgs__ctor"></a>SocketErrorEventArgs\(\)

```csharp
public SocketErrorEventArgs()
```

## Properties

### <a id="DSharpPlus_EventArgs_SocketErrorEventArgs_Exception"></a>Exception

Gets the exception thrown by websocket client.

```csharp
public Exception Exception { get; }
```

#### Property Value

[Exception](https://learn.microsoft.com/dotnet/api/system.exception)

