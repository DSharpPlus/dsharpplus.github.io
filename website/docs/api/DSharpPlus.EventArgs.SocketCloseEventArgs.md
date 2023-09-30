# Class SocketCloseEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.SocketClosed" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class SocketCloseEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[SocketCloseEventArgs](DSharpPlus.EventArgs.SocketCloseEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Constructors

### <a id="DSharpPlus_EventArgs_SocketCloseEventArgs__ctor"></a>SocketCloseEventArgs\(\)

```csharp
public SocketCloseEventArgs()
```

## Properties

### <a id="DSharpPlus_EventArgs_SocketCloseEventArgs_CloseCode"></a>CloseCode

Gets the close code sent by remote host.

```csharp
public int CloseCode { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_EventArgs_SocketCloseEventArgs_CloseMessage"></a>CloseMessage

Gets the close message sent by remote host.

```csharp
public string CloseMessage { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

