# Class DiscordWebhookClient

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents a webhook-only client. This client can be used to execute Discord webhooks.

```csharp
public class DiscordWebhookClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordWebhookClient](DSharpPlus.DiscordWebhookClient.md)

## Constructors

### <a id="DSharpPlus_DiscordWebhookClient__ctor"></a>DiscordWebhookClient\(\)

Creates a new webhook client.

```csharp
public DiscordWebhookClient()
```

### <a id="DSharpPlus_DiscordWebhookClient__ctor_System_Net_IWebProxy_System_Nullable_System_TimeSpan__System_Boolean_Microsoft_Extensions_Logging_ILoggerFactory_Microsoft_Extensions_Logging_LogLevel_System_String_"></a>DiscordWebhookClient\(IWebProxy, TimeSpan?, bool, ILoggerFactory, LogLevel, string\)

Creates a new webhook client, with specified HTTP proxy, timeout, and logging settings.

```csharp
public DiscordWebhookClient(IWebProxy proxy = null, TimeSpan? timeout = null, bool useRelativeRateLimit = true, ILoggerFactory loggerFactory = null, LogLevel minimumLogLevel = LogLevel.Information, string logTimestampFormat = "yyyy-MM-dd HH:mm:ss zzz")
```

#### Parameters

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

## Properties

### <a id="DSharpPlus_DiscordWebhookClient_AvatarUrl"></a>AvatarUrl

Gets or set the avatar override for registered webhooks. Note that this only takes effect when broadcasting.

```csharp
public string AvatarUrl { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_DiscordWebhookClient_Logger"></a>Logger

Gets the logger for this client.

```csharp
public ILogger<DiscordWebhookClient> Logger { get; }
```

#### Property Value

[ILogger](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.ilogger\-1)<[DiscordWebhookClient](DSharpPlus.DiscordWebhookClient.md)\>

### <a id="DSharpPlus_DiscordWebhookClient_Username"></a>Username

Gets or sets the username override for registered webhooks. Note that this only takes effect when broadcasting.

```csharp
public string Username { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_DiscordWebhookClient_Webhooks"></a>Webhooks

Gets the collection of registered webhooks.

```csharp
public IReadOnlyList<DiscordWebhook> Webhooks { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

## Methods

### <a id="DSharpPlus_DiscordWebhookClient_AddWebhook_DSharpPlus_Entities_DiscordWebhook_"></a>AddWebhook\(DiscordWebhook\)

Registers a webhook with this client. This reuses the supplied webhook object.

```csharp
public DiscordWebhook AddWebhook(DiscordWebhook webhook)
```

#### Parameters

`webhook` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

Webhook to register.

#### Returns

[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The registered webhook.

### <a id="DSharpPlus_DiscordWebhookClient_AddWebhookAsync_System_UInt64_System_String_"></a>AddWebhookAsync\(ulong, string\)

Registers a webhook with this client. This retrieves a webhook based on the ID and token supplied.

```csharp
public Task<DiscordWebhook> AddWebhookAsync(ulong id, string token)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the webhook to add.

`token` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the webhook to add.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

The registered webhook.

### <a id="DSharpPlus_DiscordWebhookClient_AddWebhookAsync_System_Uri_"></a>AddWebhookAsync\(Uri\)

Registers a webhook with this client. This retrieves a webhook from webhook URL.

```csharp
public Task<DiscordWebhook> AddWebhookAsync(Uri url)
```

#### Parameters

`url` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

URL of the webhook to retrieve. This URL must contain both ID and token.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

The registered webhook.

### <a id="DSharpPlus_DiscordWebhookClient_AddWebhookAsync_System_UInt64_DSharpPlus_BaseDiscordClient_"></a>AddWebhookAsync\(ulong, BaseDiscordClient\)

Registers a webhook with this client. This retrieves a webhook using the supplied full discord client.

```csharp
public Task<DiscordWebhook> AddWebhookAsync(ulong id, BaseDiscordClient client)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the webhook to register.

`client` [BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

Discord client to which the webhook will belong.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

The registered webhook.

### <a id="DSharpPlus_DiscordWebhookClient_BroadcastMessageAsync_DSharpPlus_Entities_DiscordWebhookBuilder_"></a>BroadcastMessageAsync\(DiscordWebhookBuilder\)

Broadcasts a message to all registered webhooks.

```csharp
public Task<Dictionary<DiscordWebhook, DiscordMessage>> BroadcastMessageAsync(DiscordWebhookBuilder builder)
```

#### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

Webhook builder filled with data to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[Dictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.dictionary\-2)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md), [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### <a id="DSharpPlus_DiscordWebhookClient_Finalize"></a>\~DiscordWebhookClient\(\)

```csharp
protected ~DiscordWebhookClient()
```

### <a id="DSharpPlus_DiscordWebhookClient_GetRegisteredWebhook_System_UInt64_"></a>GetRegisteredWebhook\(ulong\)

Gets a registered webhook with specified ID.

```csharp
public DiscordWebhook GetRegisteredWebhook(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the registered webhook to retrieve.

#### Returns

[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The requested webhook.

### <a id="DSharpPlus_DiscordWebhookClient_RemoveWebhook_System_UInt64_"></a>RemoveWebhook\(ulong\)

Unregisters a webhook with this client.

```csharp
public DiscordWebhook RemoveWebhook(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the webhook to unregister.

#### Returns

[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

The unregistered webhook.

