# Class LavalinkRestClient

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents a class for Lavalink REST calls.

```csharp
public sealed class LavalinkRestClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkRestClient](DSharpPlus.Lavalink.LavalinkRestClient.md)

## Constructors

### <a id="DSharpPlus_Lavalink_LavalinkRestClient__ctor_DSharpPlus_Net_ConnectionEndpoint_System_String_"></a>LavalinkRestClient\(ConnectionEndpoint, string\)

Creates a new Lavalink REST client.

```csharp
public LavalinkRestClient(ConnectionEndpoint restEndpoint, string password)
```

#### Parameters

`restEndpoint` [ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md)

The REST server endpoint to connect to.

`password` [string](https://learn.microsoft.com/dotnet/api/system.string)

The password for the remote server.

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_RestEndpoint"></a>RestEndpoint

Gets the REST connection endpoint for this client.

```csharp
public ConnectionEndpoint RestEndpoint { get; }
```

#### Property Value

[ConnectionEndpoint](DSharpPlus.Net.ConnectionEndpoint.md)

## Methods

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_DecodeTrackAsync_System_String_"></a>DecodeTrackAsync\(string\)

Decodes a base64 track string into a Lavalink track object.

```csharp
public Task<LavalinkTrack> DecodeTrackAsync(string trackString)
```

#### Parameters

`trackString` [string](https://learn.microsoft.com/dotnet/api/system.string)

The base64 track string.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)\>

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_DecodeTracksAsync_System_String___"></a>DecodeTracksAsync\(string\[\]\)

Decodes an array of base64 track strings into Lavalink track objects.

```csharp
public Task<IEnumerable<LavalinkTrack>> DecodeTracksAsync(string[] trackStrings)
```

#### Parameters

`trackStrings` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

The array of base64 track strings.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)\>\>

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_DecodeTracksAsync_System_Collections_Generic_List_System_String__"></a>DecodeTracksAsync\(List<string\>\)

Decodes a list of base64 track strings into Lavalink track objects.

```csharp
public Task<IEnumerable<LavalinkTrack>> DecodeTracksAsync(List<string> trackStrings)
```

#### Parameters

`trackStrings` [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

The list of base64 track strings.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)\>\>

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_FreeAddressAsync_System_String_"></a>FreeAddressAsync\(string\)

Unmarks a failed route planner IP Address.

```csharp
public Task FreeAddressAsync(string address)
```

#### Parameters

`address` [string](https://learn.microsoft.com/dotnet/api/system.string)

The IP address name to unmark.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_FreeAllAddressesAsync"></a>FreeAllAddressesAsync\(\)

Unmarks all failed route planner IP Addresses.

```csharp
public Task FreeAllAddressesAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetRoutePlannerStatusAsync"></a>GetRoutePlannerStatusAsync\(\)

Retrieves statistics from the route planner.

```csharp
public Task<LavalinkRouteStatus> GetRoutePlannerStatusAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkRouteStatus](DSharpPlus.Lavalink.Entities.LavalinkRouteStatus.md)\>

The status (<xref href="DSharpPlus.Lavalink.Entities.LavalinkRouteStatus" data-throw-if-not-resolved="false"></xref>) details.

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetTracksAsync_System_String_DSharpPlus_Lavalink_LavalinkSearchType_"></a>GetTracksAsync\(string, LavalinkSearchType\)

Searches for specified terms.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(string searchQuery, LavalinkSearchType type = LavalinkSearchType.Youtube)
```

#### Parameters

`searchQuery` [string](https://learn.microsoft.com/dotnet/api/system.string)

What to search for.

`type` [LavalinkSearchType](DSharpPlus.Lavalink.LavalinkSearchType.md)

What platform will search for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks matching the criteria.

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetTracksAsync_System_Uri_"></a>GetTracksAsync\(Uri\)

Loads tracks from specified URL.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(Uri uri)
```

#### Parameters

`uri` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

URL to load tracks from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks from the URL.

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetTracksAsync_System_IO_FileInfo_"></a>GetTracksAsync\(FileInfo\)

Loads tracks from a local file.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(FileInfo file)
```

#### Parameters

`file` [FileInfo](https://learn.microsoft.com/dotnet/api/system.io.fileinfo)

File to load tracks from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks from the file.

### <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetVersionAsync"></a>GetVersionAsync\(\)

Gets the version of the Lavalink server.

```csharp
public Task<string> GetVersionAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

