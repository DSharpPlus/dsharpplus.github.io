# Class LavalinkLoadResult

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents information about track loading request.

```csharp
public class LavalinkLoadResult
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkLoadResult](DSharpPlus.Lavalink.LavalinkLoadResult.md)

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkLoadResult_Exception"></a>Exception

Gets the exception details if a track loading failed.

```csharp
[JsonProperty("exception", NullValueHandling = NullValueHandling.Ignore)]
public LavalinkLoadFailedInfo Exception { get; }
```

#### Property Value

[LavalinkLoadFailedInfo](DSharpPlus.Lavalink.LavalinkLoadFailedInfo.md)

### <a id="DSharpPlus_Lavalink_LavalinkLoadResult_LoadResultType"></a>LoadResultType

Gets the loading result type for this request.

```csharp
[JsonProperty("loadType")]
public LavalinkLoadResultType LoadResultType { get; }
```

#### Property Value

[LavalinkLoadResultType](DSharpPlus.Lavalink.LavalinkLoadResultType.md)

### <a id="DSharpPlus_Lavalink_LavalinkLoadResult_PlaylistInfo"></a>PlaylistInfo

<p>Gets the information about the playlist loaded as a result of this request.</p>
<p>Only applicable if <xref href="DSharpPlus.Lavalink.LavalinkLoadResult.LoadResultType" data-throw-if-not-resolved="false"></xref> is set to <xref href="DSharpPlus.Lavalink.LavalinkLoadResultType.PlaylistLoaded" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("playlistInfo")]
public LavalinkPlaylistInfo PlaylistInfo { get; }
```

#### Property Value

[LavalinkPlaylistInfo](DSharpPlus.Lavalink.LavalinkPlaylistInfo.md)

### <a id="DSharpPlus_Lavalink_LavalinkLoadResult_Tracks"></a>Tracks

Gets the tracks that were loaded as a result of this request.

```csharp
[JsonIgnore]
public IEnumerable<LavalinkTrack> Tracks { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)\>

