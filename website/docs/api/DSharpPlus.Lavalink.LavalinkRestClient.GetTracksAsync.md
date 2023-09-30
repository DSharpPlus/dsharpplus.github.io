# Method GetTracksAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetTracksAsync_System_String_DSharpPlus_Lavalink_LavalinkSearchType_"></a>GetTracksAsync\(string, LavalinkSearchType\)

Searches for specified terms.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(string searchQuery, LavalinkSearchType type = LavalinkSearchType.Youtube)
```

### Parameters

`searchQuery` [string](https://learn.microsoft.com/dotnet/api/system.string)

What to search for.

`type` [LavalinkSearchType](DSharpPlus.Lavalink.LavalinkSearchType.md)

What platform will search for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks matching the criteria.

## <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetTracksAsync_System_Uri_"></a>GetTracksAsync\(Uri\)

Loads tracks from specified URL.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(Uri uri)
```

### Parameters

`uri` [Uri](https://learn.microsoft.com/dotnet/api/system.uri)

URL to load tracks from.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks from the URL.

## <a id="DSharpPlus_Lavalink_LavalinkRestClient_GetTracksAsync_System_IO_FileInfo_"></a>GetTracksAsync\(FileInfo\)

Loads tracks from a local file.

```csharp
public Task<LavalinkLoadResult> GetTracksAsync(FileInfo file)
```

### Parameters

`file` [FileInfo](https://learn.microsoft.com/dotnet/api/system.io.fileinfo)

File to load tracks from.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)\>

A collection of tracks from the file.

