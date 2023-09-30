# Struct LavalinkPlaylistInfo

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents information about playlist that was loaded by Lavalink.

```csharp
public struct LavalinkPlaylistInfo
```

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkPlaylistInfo_Name"></a>Name

Gets the name of the playlist being loaded.

```csharp
[JsonProperty("name")]
public readonly string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkPlaylistInfo_SelectedTrack"></a>SelectedTrack

Gets the index of the track that was selected in this playlist.

```csharp
[JsonProperty("selectedTrack")]
public readonly int SelectedTrack { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

