# Property PlaylistInfo

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkLoadResult_PlaylistInfo"></a>PlaylistInfo

<p>Gets the information about the playlist loaded as a result of this request.</p>
<p>Only applicable if <xref href="DSharpPlus.Lavalink.LavalinkLoadResult.LoadResultType" data-throw-if-not-resolved="false"></xref> is set to <xref href="DSharpPlus.Lavalink.LavalinkLoadResultType.PlaylistLoaded" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
[JsonProperty("playlistInfo")]
public LavalinkPlaylistInfo PlaylistInfo { get; }
```

### Property Value

[LavalinkPlaylistInfo](DSharpPlus.Lavalink.LavalinkPlaylistInfo.md)

