# Class LavalinkNodeConnection

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents a connection to a Lavalink node.

```csharp
public sealed class LavalinkNodeConnection
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_ConnectedGuilds"></a>ConnectedGuilds

Gets a dictionary of Lavalink guild connections for this node.

```csharp
public IReadOnlyDictionary<ulong, LavalinkGuildConnection> ConnectedGuilds { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_Discord"></a>Discord

Gets the Discord client this node connection belongs to.

```csharp
public DiscordClient Discord { get; }
```

#### Property Value

[DiscordClient](DSharpPlus.DiscordClient.md)

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_IsConnected"></a>IsConnected

Gets whether the client is connected to Lavalink.

```csharp
public bool IsConnected { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_NodeEndpoint"></a>NodeEndpoint

Gets the remote endpoint of this Lavalink node connection.

```csharp
public ConnectionEndpoint NodeEndpoint { get; }
```

#### Property Value

[ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md)

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_Parent"></a>Parent

Gets the parent extension which this node connection belongs to.

```csharp
public LavalinkExtension Parent { get; }
```

#### Property Value

[LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_Rest"></a>Rest

Gets the REST client for this Lavalink connection.

```csharp
public LavalinkRestClient Rest { get; }
```

#### Property Value

[LavalinkRestClient](DSharpPlus.Lavalink.LavalinkRestClient.md)

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_Statistics"></a>Statistics

Gets the current resource usage statistics.

```csharp
public LavalinkStatistics Statistics { get; }
```

#### Property Value

[LavalinkStatistics](DSharpPlus.Lavalink.Entities.LavalinkStatistics.md)

## Methods

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_ConnectAsync_DSharpPlus_Entities_DiscordChannel_"></a>ConnectAsync\(DiscordChannel\)

Connects this Lavalink node to specified Discord channel.

```csharp
public Task<LavalinkGuildConnection> ConnectAsync(DiscordChannel channel)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Voice channel to connect to.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)\>

Channel connection, which allows for playback control.

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_GetGuildConnection_DSharpPlus_Entities_DiscordGuild_"></a>GetGuildConnection\(DiscordGuild\)

Gets a Lavalink connection to specified Discord channel.

```csharp
public LavalinkGuildConnection GetGuildConnection(DiscordGuild guild)
```

#### Parameters

`guild` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

Guild to get connection for.

#### Returns

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

Channel connection, which allows for playback control.

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_StopAsync"></a>StopAsync\(\)

Stops this Lavalink node connection and frees resources.

```csharp
public Task StopAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_Disconnected"></a>Disconnected

Triggered when this node disconnects.

```csharp
public event AsyncEventHandler<LavalinkNodeConnection, NodeDisconnectedEventArgs> Disconnected
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md), [NodeDisconnectedEventArgs](DSharpPlus.Lavalink.EventArgs.NodeDisconnectedEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_GuildConnectionCreated"></a>GuildConnectionCreated

Triggered whenever a new guild connection is created.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, GuildConnectionCreatedEventArgs> GuildConnectionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [GuildConnectionCreatedEventArgs](DSharpPlus.Lavalink.EventArgs.GuildConnectionCreatedEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_GuildConnectionRemoved"></a>GuildConnectionRemoved

Triggered whenever a guild connection is removed.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, GuildConnectionRemovedEventArgs> GuildConnectionRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [GuildConnectionRemovedEventArgs](DSharpPlus.Lavalink.EventArgs.GuildConnectionRemovedEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_LavalinkSocketErrored"></a>LavalinkSocketErrored

Triggered whenever Lavalink WebSocket throws an exception.

```csharp
public event AsyncEventHandler<LavalinkNodeConnection, SocketErrorEventArgs> LavalinkSocketErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md), [SocketErrorEventArgs](DSharpPlus.EventArgs.SocketErrorEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_PlaybackFinished"></a>PlaybackFinished

Triggered whenever playback of a track finishes.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackFinishEventArgs> PlaybackFinished
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackFinishEventArgs](DSharpPlus.Lavalink.EventArgs.TrackFinishEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_PlaybackStarted"></a>PlaybackStarted

Triggered whenever playback of a track starts.
<p>This is only available for version 3.3.1 and greater.</p>

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackStartEventArgs> PlaybackStarted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackStartEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStartEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_PlayerUpdated"></a>PlayerUpdated

Triggered whenever any of the players on this node is updated.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, PlayerUpdateEventArgs> PlayerUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [PlayerUpdateEventArgs](DSharpPlus.Lavalink.EventArgs.PlayerUpdateEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_StatisticsReceived"></a>StatisticsReceived

Triggered when this node receives a statistics update.

```csharp
public event AsyncEventHandler<LavalinkNodeConnection, StatisticsReceivedEventArgs> StatisticsReceived
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md), [StatisticsReceivedEventArgs](DSharpPlus.Lavalink.EventArgs.StatisticsReceivedEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_TrackException"></a>TrackException

Triggered whenever playback of a track encounters an error.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackExceptionEventArgs> TrackException
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackExceptionEventArgs](DSharpPlus.Lavalink.EventArgs.TrackExceptionEventArgs.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_TrackStuck"></a>TrackStuck

Triggered whenever playback of a track gets stuck.

```csharp
public event AsyncEventHandler<LavalinkGuildConnection, TrackStuckEventArgs> TrackStuck
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md), [TrackStuckEventArgs](DSharpPlus.Lavalink.EventArgs.TrackStuckEventArgs.md)\>

