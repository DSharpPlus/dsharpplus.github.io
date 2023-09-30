# Class DiscordConfiguration

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents configuration for <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordConfiguration
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordConfiguration](DSharpPlus.DiscordConfiguration.md)

## Constructors

### <a id="DSharpPlus_DiscordConfiguration__ctor"></a>DiscordConfiguration\(\)

Creates a new configuration with default values.

```csharp
public DiscordConfiguration()
```

### <a id="DSharpPlus_DiscordConfiguration__ctor_DSharpPlus_DiscordConfiguration_"></a>DiscordConfiguration\(DiscordConfiguration\)

Creates a clone of another discord configuration.

```csharp
public DiscordConfiguration(DiscordConfiguration other)
```

#### Parameters

`other` [DiscordConfiguration](DSharpPlus.DiscordConfiguration.md)

Client configuration to clone.

## Properties

### <a id="DSharpPlus_DiscordConfiguration_AlwaysCacheMembers"></a>AlwaysCacheMembers

Sets whether the client should attempt to cache members if exclusively using unprivileged intents.
<p>
    This will only take effect if there are no <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref>
    intents specified. Otherwise, this will always be overwritten to true.
</p>
<p>Defaults to true.</p>

```csharp
public bool AlwaysCacheMembers { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_DiscordConfiguration_AutoReconnect"></a>AutoReconnect

<p>Sets whether to automatically reconnect in case a connection is lost.</p>
<p>Defaults to true.</p>

```csharp
public bool AutoReconnect { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_DiscordConfiguration_GatewayCompressionLevel"></a>GatewayCompressionLevel

<p>Sets the level of compression for WebSocket traffic.</p>
<p>Disabling this option will increase the amount of traffic sent via WebSocket. Setting <xref href="DSharpPlus.GatewayCompressionLevel.Payload" data-throw-if-not-resolved="false"></xref> will enable compression for READY and GUILD_CREATE payloads. Setting <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref> will enable compression for the entire WebSocket stream, drastically reducing amount of traffic.</p>
<p>Defaults to <xref href="System.IO.Stream" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public GatewayCompressionLevel GatewayCompressionLevel { set; }
```

#### Property Value

[GatewayCompressionLevel](DSharpPlus.GatewayCompressionLevel.md)

### <a id="DSharpPlus_DiscordConfiguration_HttpTimeout"></a>HttpTimeout

<p>Sets the timeout for HTTP requests.</p>
<p>Set to <xref href="System.Threading.Timeout.InfiniteTimeSpan" data-throw-if-not-resolved="false"></xref> to disable timeouts.</p>
<p>Defaults to 10 seconds.</p>

```csharp
public TimeSpan HttpTimeout { set; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

### <a id="DSharpPlus_DiscordConfiguration_Intents"></a>Intents

<p>Sets the gateway intents for this client.</p>
<p>If set, the client will only receive events that they specify with intents.</p>
<p>Defaults to <xref href="DSharpPlus.DiscordIntents.AllUnprivileged" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public DiscordIntents Intents { set; }
```

#### Property Value

[DiscordIntents](DSharpPlus.DiscordIntents.md)

### <a id="DSharpPlus_DiscordConfiguration_LargeThreshold"></a>LargeThreshold

<p>Sets the member count threshold at which guilds are considered large.</p>
<p>Defaults to 250.</p>

```csharp
public int LargeThreshold { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_DiscordConfiguration_LogTimestampFormat"></a>LogTimestampFormat

<p>Allows you to overwrite the time format used by the internal debug logger.</p>
<p>Only applicable when <xref href="DSharpPlus.DiscordConfiguration.LoggerFactory" data-throw-if-not-resolved="false"></xref> is set left at default value. Defaults to ISO 8601-like format.</p>

```csharp
public string LogTimestampFormat { set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_DiscordConfiguration_LogUnknownAuditlogs"></a>LogUnknownAuditlogs

Whether to log unknown auditlog types and change keys or not. Defaults to true.

```csharp
public bool LogUnknownAuditlogs { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_DiscordConfiguration_LogUnknownEvents"></a>LogUnknownEvents

Whether to log unknown events or not. Defaults to true.

```csharp
public bool LogUnknownEvents { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_DiscordConfiguration_LoggerFactory"></a>LoggerFactory

<p>Sets the logger implementation to use.</p>
<p>To create your own logger, implement the <xref href="Microsoft.Extensions.Logging.ILoggerFactory" data-throw-if-not-resolved="false"></xref> instance.</p>
<p>Defaults to built-in implementation.</p>

```csharp
public ILoggerFactory LoggerFactory { set; }
```

#### Property Value

[ILoggerFactory](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.iloggerfactory)

### <a id="DSharpPlus_DiscordConfiguration_MessageCacheProvider"></a>MessageCacheProvider

<p>Sets the message cache implementation to use.</p>
<p>To create your own implementation, implement the <xref href="DSharpPlus.IMessageCacheProvider" data-throw-if-not-resolved="false"></xref> instance.</p>
<p>Defaults to built-in implementation.</p>

```csharp
public IMessageCacheProvider? MessageCacheProvider { set; }
```

#### Property Value

[IMessageCacheProvider](DSharpPlus.IMessageCacheProvider.md)?

### <a id="DSharpPlus_DiscordConfiguration_MessageCacheSize"></a>MessageCacheSize

<p>Sets the size of the global message cache.</p>
<p>Setting this to 0 will disable message caching entirely. Defaults to 1024.</p>
<p>This is only applied if the default message cache implementation is used.</p>

```csharp
public int MessageCacheSize { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_DiscordConfiguration_MinimumLogLevel"></a>MinimumLogLevel

<p>Sets the minimum logging level for messages.</p>
<p>Typically, the default value of <xref href="Microsoft.Extensions.Logging.LogLevel.Information" data-throw-if-not-resolved="false"></xref> is ok for most uses.</p>

```csharp
public LogLevel MinimumLogLevel { set; }
```

#### Property Value

[LogLevel](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.loglevel)

### <a id="DSharpPlus_DiscordConfiguration_Proxy"></a>Proxy

<p>Sets the proxy to use for HTTP and WebSocket connections to Discord.</p>
<p>Defaults to null.</p>

```csharp
public IWebProxy Proxy { set; }
```

#### Property Value

[IWebProxy](https://learn.microsoft.com/dotnet/api/system.net.iwebproxy)

### <a id="DSharpPlus_DiscordConfiguration_ReconnectIndefinitely"></a>ReconnectIndefinitely

<p>Defines that the client should attempt to reconnect indefinitely.</p>
<p>This is typically a very bad idea to set to <code>true</code>, as it will swallow all connection errors.</p>
<p>Defaults to false.</p>

```csharp
public bool ReconnectIndefinitely { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_DiscordConfiguration_ShardCount"></a>ShardCount

<p>Sets the total number of shards the bot is on. If not sharding, this value should be left with a default value of 1.</p>
<p>If sharding automatically, this value will indicate how many shards to boot. If left default for automatic sharding, the client will determine the shard count automatically.</p>

```csharp
public int ShardCount { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_DiscordConfiguration_ShardId"></a>ShardId

<p>Sets the ID of the shard to connect to.</p>
<p>If not sharding, or sharding automatically, this value should be left with the default value of 0.</p>

```csharp
public int ShardId { set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_DiscordConfiguration_Token"></a>Token

Sets the token used to identify the client.

```csharp
public string Token { set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_DiscordConfiguration_TokenType"></a>TokenType

<p>Sets the type of the token used to identify the client.</p>
<p>Defaults to <xref href="DSharpPlus.TokenType.Bot" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public TokenType TokenType { set; }
```

#### Property Value

[TokenType](DSharpPlus.TokenType.md)

### <a id="DSharpPlus_DiscordConfiguration_UdpClientFactory"></a>UdpClientFactory

<p>Sets the factory method used to create instances of UDP clients.</p>
<p>Use <xref href="DSharpPlus.Net.Udp.DspUdpClient.CreateNew" data-throw-if-not-resolved="false"></xref> and equivalents on other implementations to switch out client implementations.</p>
<p>Defaults to <xref href="DSharpPlus.Net.Udp.DspUdpClient.CreateNew" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public UdpClientFactoryDelegate UdpClientFactory { set; }
```

#### Property Value

[UdpClientFactoryDelegate](DSharpPlus.Net.Udp.UdpClientFactoryDelegate.md)

### <a id="DSharpPlus_DiscordConfiguration_UseRelativeRatelimit"></a>UseRelativeRatelimit

<p>Sets whether to rely on Discord for NTP (Network Time Protocol) synchronization with the "X-Ratelimit-Reset-After" header.</p>
<p>If the system clock is not synced, setting this to true will ensure ratelimits are synced with Discord and reduce the risk of hitting one.</p>
<p>This should only be set to false if the system clock is synced with NTP.</p>
<p>Defaults to true.</p>

```csharp
public bool UseRelativeRatelimit { set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_DiscordConfiguration_WebSocketClientFactory"></a>WebSocketClientFactory

<p>Sets the factory method used to create instances of WebSocket clients.</p>
<p>Use <xref href="DSharpPlus.Net.WebSocket.WebSocketClient.CreateNew(System.Net.IWebProxy)" data-throw-if-not-resolved="false"></xref> and equivalents on other implementations to switch out client implementations.</p>
<p>Defaults to <xref href="DSharpPlus.Net.WebSocket.WebSocketClient.CreateNew(System.Net.IWebProxy)" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public WebSocketClientFactoryDelegate WebSocketClientFactory { set; }
```

#### Property Value

[WebSocketClientFactoryDelegate](DSharpPlus.Net.WebSocket.WebSocketClientFactoryDelegate.md)

