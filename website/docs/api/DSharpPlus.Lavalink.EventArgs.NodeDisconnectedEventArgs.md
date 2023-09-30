# Class NodeDisconnectedEventArgs

Namespace: [DSharpPlus.Lavalink.EventArgs](DSharpPlus.Lavalink.EventArgs.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents event arguments for Lavalink node disconnection.

```csharp
public sealed class NodeDisconnectedEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[NodeDisconnectedEventArgs](DSharpPlus.Lavalink.EventArgs.NodeDisconnectedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_Lavalink_EventArgs_NodeDisconnectedEventArgs_IsCleanClose"></a>IsCleanClose

Gets whether disconnect was clean.

```csharp
public bool IsCleanClose { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Lavalink_EventArgs_NodeDisconnectedEventArgs_LavalinkNode"></a>LavalinkNode

Gets the node that was disconnected.

```csharp
public LavalinkNodeConnection LavalinkNode { get; }
```

#### Property Value

[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

