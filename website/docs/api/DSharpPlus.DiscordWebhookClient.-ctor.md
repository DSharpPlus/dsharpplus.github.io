# Constructor DiscordWebhookClient

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordWebhookClient__ctor"></a>DiscordWebhookClient\(\)

Creates a new webhook client.

```csharp
public DiscordWebhookClient()
```

## <a id="DSharpPlus_DiscordWebhookClient__ctor_System_Net_IWebProxy_System_Nullable_System_TimeSpan__System_Boolean_Microsoft_Extensions_Logging_ILoggerFactory_Microsoft_Extensions_Logging_LogLevel_System_String_"></a>DiscordWebhookClient\(IWebProxy, TimeSpan?, bool, ILoggerFactory, LogLevel, string\)

Creates a new webhook client, with specified HTTP proxy, timeout, and logging settings.

```csharp
public DiscordWebhookClient(IWebProxy proxy = null, TimeSpan? timeout = null, bool useRelativeRateLimit = true, ILoggerFactory loggerFactory = null, LogLevel minimumLogLevel = LogLevel.Information, string logTimestampFormat = "yyyy-MM-dd HH:mm:ss zzz")
```

### Parameters

`proxy` [IWebProxy](https://learn.microsoft.com/dotnet/api/system.net.iwebproxy)

Proxy to use for HTTP connections.

`timeout` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Timeout to use for HTTP requests. Set to <xref href="System.Threading.Timeout.InfiniteTimeSpan" data-throw-if-not-resolved="false"></xref> to disable timeouts.

`useRelativeRateLimit` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to use the system clock for computing rate limit resets. See <xref href="DSharpPlus.DiscordConfiguration.UseRelativeRatelimit" data-throw-if-not-resolved="false"></xref> for more details.

`loggerFactory` [ILoggerFactory](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.iloggerfactory)

The optional logging factory to use for this client.

`minimumLogLevel` [LogLevel](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.loglevel)

The minimum logging level for messages.

`logTimestampFormat` [string](https://learn.microsoft.com/dotnet/api/system.string)

The timestamp format to use for the logger.

