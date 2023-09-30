# Class LavalinkExtension

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

```csharp
public sealed class LavalinkExtension : BaseExtension
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseExtension](DSharpPlus.BaseExtension.md) ← 
[LavalinkExtension](DSharpPlus.Lavalink.LavalinkExtension.md)

###### Inherited Members

[BaseExtension.Client](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Client), 
[BaseExtension.Dispose\(\)](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Dispose)

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkExtension_ConnectedNodes"></a>ConnectedNodes

Gets a dictionary of connected Lavalink nodes for the extension.

```csharp
public IReadOnlyDictionary<ConnectionEndpoint, LavalinkNodeConnection> ConnectedNodes { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md), [LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)\>

## Methods

### <a id="DSharpPlus_Lavalink_LavalinkExtension_ConnectAsync_DSharpPlus_Lavalink_LavalinkConfiguration_"></a>ConnectAsync\(LavalinkConfiguration\)

Connect to a Lavalink node.

```csharp
public Task<LavalinkNodeConnection> ConnectAsync(LavalinkConfiguration config)
```

#### Parameters

`config` [LavalinkConfiguration](DSharpPlus.Lavalink.LavalinkConfiguration.md)

Lavalink client configuration.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)\>

The established Lavalink connection.

### <a id="DSharpPlus_Lavalink_LavalinkExtension_Dispose"></a>Dispose\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

```csharp
public override void Dispose()
```

### <a id="DSharpPlus_Lavalink_LavalinkExtension_GetGuildConnection_DSharpPlus_Entities_DiscordGuild_"></a>GetGuildConnection\(DiscordGuild\)

Gets a Lavalink guild connection from a <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref>.

```csharp
public LavalinkGuildConnection GetGuildConnection(DiscordGuild guild)
```

#### Parameters

`guild` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

The guild the connection is on.

#### Returns

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

The found guild connection, or null if one could not be found.

### <a id="DSharpPlus_Lavalink_LavalinkExtension_GetIdealNodeConnection_DSharpPlus_Entities_DiscordVoiceRegion_"></a>GetIdealNodeConnection\(DiscordVoiceRegion\)

Gets a Lavalink node connection based on load balancing and an optional voice region.

```csharp
public LavalinkNodeConnection GetIdealNodeConnection(DiscordVoiceRegion region = null)
```

#### Parameters

`region` [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

The region to compare with the node's <xref href="DSharpPlus.Lavalink.LavalinkConfiguration.Region" data-throw-if-not-resolved="false"></xref>, if any.

#### Returns

[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

The least load affected node connection, or null if no nodes are present.

### <a id="DSharpPlus_Lavalink_LavalinkExtension_GetNodeConnection_DSharpPlus_Net_ConnectionEndpoint_"></a>GetNodeConnection\(ConnectionEndpoint\)

Gets the Lavalink node connection for the specified endpoint.

```csharp
public LavalinkNodeConnection GetNodeConnection(ConnectionEndpoint endpoint)
```

#### Parameters

`endpoint` [ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md)

Endpoint at which the node resides.

#### Returns

[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

Lavalink node connection.

### <a id="DSharpPlus_Lavalink_LavalinkExtension_Setup_DSharpPlus_DiscordClient_"></a>Setup\(DiscordClient\)

DO NOT USE THIS MANUALLY.

```csharp
protected override void Setup(DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

DO NOT USE THIS MANUALLY.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

### <a id="DSharpPlus_Lavalink_LavalinkExtension_NodeDisconnected"></a>NodeDisconnected

Triggered whenever a node disconnects.

```csharp
public event AsyncEventHandler<LavalinkNodeConnection, NodeDisconnectedEventArgs> NodeDisconnected
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md), [NodeDisconnectedEventArgs](DSharpPlus.Lavalink.EventArgs.NodeDisconnectedEventArgs.md)\>

