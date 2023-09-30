# Class LavalinkConfiguration

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Lavalink connection configuration.

```csharp
public sealed class LavalinkConfiguration
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkConfiguration](DSharpPlus.Lavalink.LavalinkConfiguration.md)

## Constructors

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration__ctor"></a>LavalinkConfiguration\(\)

Creates a new instance of <xref href="DSharpPlus.Lavalink.LavalinkConfiguration" data-throw-if-not-resolved="false"></xref>.

```csharp
public LavalinkConfiguration()
```

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration__ctor_DSharpPlus_Lavalink_LavalinkConfiguration_"></a>LavalinkConfiguration\(LavalinkConfiguration\)

Creates a new instance of <xref href="DSharpPlus.Lavalink.LavalinkConfiguration" data-throw-if-not-resolved="false"></xref>, copying the properties of another configuration.

```csharp
public LavalinkConfiguration(LavalinkConfiguration other)
```

#### Parameters

`other` [LavalinkConfiguration](DSharpPlus.Lavalink.LavalinkConfiguration.md)

Configuration the properties of which are to be copied.

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_Password"></a>Password

Sets the password for the Lavalink connection.
<p>Defaults to "youshallnotpass".</p>

```csharp
public string Password { set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_Region"></a>Region

Sets the voice region ID for the Lavalink connection.
<p>This should be used if nodes should be filtered by region with <xref href="DSharpPlus.Lavalink.LavalinkExtension.GetIdealNodeConnection(DSharpPlus.Entities.DiscordVoiceRegion)" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public DiscordVoiceRegion Region { set; }
```

#### Property Value

[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_RestEndpoint"></a>RestEndpoint

Sets the endpoint for Lavalink REST.
<p>Defaults to 127.0.0.1 on port 2333.</p>

```csharp
public ConnectionEndpoint RestEndpoint { set; }
```

#### Property Value

[ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md)

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_ResumeKey"></a>ResumeKey

Sets the resume key for the Lavalink connection.
<p>This will allow existing voice sessions to continue for a certain time after the client is disconnected.</p>

```csharp
public string ResumeKey { set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_ResumeTimeout"></a>ResumeTimeout

Sets the time in seconds when all voice sessions are closed after the client disconnects.
<p>Defaults to 60 seconds.</p>

```csharp
public int ResumeTimeout { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_SocketAutoReconnect"></a>SocketAutoReconnect

Sets whether the connection wrapper should attempt automatic reconnects should the connection drop.
<p>Defaults to true.</p>

```csharp
public bool SocketAutoReconnect { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_SocketEndpoint"></a>SocketEndpoint

Sets the endpoint for the Lavalink Websocket connection.
<p>Defaults to 127.0.0.1 on port 2333.</p>

```csharp
public ConnectionEndpoint SocketEndpoint { set; }
```

#### Property Value

[ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md)

### <a id="DSharpPlus_Lavalink_LavalinkConfiguration_WebSocketCloseTimeout"></a>WebSocketCloseTimeout

Sets the time in milliseconds to wait for Lavalink's voice WebSocket to close after leaving a voice channel.
<p>This will be the delay before the guild connection is removed.</p>
<p>Defaults to 3000 milliseconds.</p>

```csharp
public int WebSocketCloseTimeout { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

