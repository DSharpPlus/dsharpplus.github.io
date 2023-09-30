# Class BaseDiscordClient

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents a common base for various Discord client implementations.

```csharp
public abstract class BaseDiscordClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)

###### Derived

[DiscordClient](DSharpPlus.DiscordClient.md), 
[DiscordRestClient](DSharpPlus.DiscordRestClient.md)

## Constructors

### <a id="DSharpPlus_BaseDiscordClient__ctor_DSharpPlus_DiscordConfiguration_"></a>BaseDiscordClient\(DiscordConfiguration\)

Initializes this Discord API client.

```csharp
protected BaseDiscordClient(DiscordConfiguration config)
```

#### Parameters

`config` [DiscordConfiguration](DSharpPlus.DiscordConfiguration.md)

Configuration for this client.

## Properties

### <a id="DSharpPlus_BaseDiscordClient_ApiClient"></a>ApiClient

```csharp
protected DiscordApiClient ApiClient { get; }
```

#### Property Value

[DiscordApiClient](DSharpPlus.Net.DiscordApiClient.md)

### <a id="DSharpPlus_BaseDiscordClient_Configuration"></a>Configuration

```csharp
protected DiscordConfiguration Configuration { get; }
```

#### Property Value

[DiscordConfiguration](DSharpPlus.DiscordConfiguration.md)

### <a id="DSharpPlus_BaseDiscordClient_CurrentApplication"></a>CurrentApplication

Gets the current application.

```csharp
public DiscordApplication CurrentApplication { get; }
```

#### Property Value

[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

### <a id="DSharpPlus_BaseDiscordClient_CurrentUser"></a>CurrentUser

Gets the current user.

```csharp
public DiscordUser CurrentUser { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_BaseDiscordClient_Guilds"></a>Guilds

Gets the cached guilds for this client.

```csharp
public abstract IReadOnlyDictionary<ulong, DiscordGuild> Guilds { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

### <a id="DSharpPlus_BaseDiscordClient_InternalVoiceRegions"></a>InternalVoiceRegions

Gets the list of available voice regions. This property is meant as a way to modify <xref href="DSharpPlus.BaseDiscordClient.VoiceRegions" data-throw-if-not-resolved="false"></xref>.

```csharp
protected ConcurrentDictionary<string, DiscordVoiceRegion> InternalVoiceRegions { get; set; }
```

#### Property Value

[ConcurrentDictionary](https://learn.microsoft.com/dotnet/api/system.collections.concurrent.concurrentdictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>

### <a id="DSharpPlus_BaseDiscordClient_Logger"></a>Logger

Gets the instance of the logger for this client.

```csharp
public ILogger<BaseDiscordClient> Logger { get; }
```

#### Property Value

[ILogger](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.ilogger\-1)<[BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)\>

### <a id="DSharpPlus_BaseDiscordClient_UserCache"></a>UserCache

Gets the cached users for this client.

```csharp
protected ConcurrentDictionary<ulong, DiscordUser> UserCache { get; }
```

#### Property Value

[ConcurrentDictionary](https://learn.microsoft.com/dotnet/api/system.collections.concurrent.concurrentdictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_BaseDiscordClient_VersionString"></a>VersionString

Gets the string representing the version of D#+.

```csharp
public string VersionString { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_BaseDiscordClient_VoiceRegions"></a>VoiceRegions

Gets the list of available voice regions. Note that this property will not contain VIP voice regions.

```csharp
public IReadOnlyDictionary<string, DiscordVoiceRegion> VoiceRegions { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>

## Methods

### <a id="DSharpPlus_BaseDiscordClient_Dispose"></a>Dispose\(\)

Disposes this client.

```csharp
public abstract void Dispose()
```

### <a id="DSharpPlus_BaseDiscordClient_GetCurrentApplicationAsync"></a>GetCurrentApplicationAsync\(\)

Gets the current API application.

```csharp
public Task<DiscordApplication> GetCurrentApplicationAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)\>

Current API application.

### <a id="DSharpPlus_BaseDiscordClient_GetGatewayInfoAsync_System_String_"></a>GetGatewayInfoAsync\(string\)

Gets the current gateway info for the provided token.
<p>If no value is provided, the configuration value will be used instead.</p>

```csharp
public Task<GatewayInfo> GetGatewayInfoAsync(string token = null)
```

#### Parameters

`token` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[GatewayInfo](DSharpPlus.Net.GatewayInfo.md)\>

A gateway info object.

### <a id="DSharpPlus_BaseDiscordClient_InitializeAsync"></a>InitializeAsync\(\)

Initializes this client. This method fetches information about current user, application, and voice regions.

```csharp
public virtual Task InitializeAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_BaseDiscordClient_ListVoiceRegionsAsync"></a>ListVoiceRegionsAsync\(\)

Gets a list of regions

```csharp
public Task<IReadOnlyList<DiscordVoiceRegion>> ListVoiceRegionsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>\>

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

