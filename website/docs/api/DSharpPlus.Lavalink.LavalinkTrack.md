# Class LavalinkTrack

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

```csharp
public class LavalinkTrack
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkTrack_Author"></a>Author

Gets the author of the track.

```csharp
[JsonProperty("author")]
public string Author { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_Identifier"></a>Identifier

Gets the identifier of the track.

```csharp
[JsonProperty("identifier")]
public string Identifier { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_IsSeekable"></a>IsSeekable

Gets whether the track is seekable.

```csharp
[JsonProperty("isSeekable")]
public bool IsSeekable { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_IsStream"></a>IsStream

Gets whether the track is a stream.

```csharp
[JsonProperty("isStream")]
public bool IsStream { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_Length"></a>Length

Gets the track's duration.

```csharp
[JsonIgnore]
public TimeSpan Length { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_Position"></a>Position

Gets the starting position of the track.

```csharp
[JsonIgnore]
public TimeSpan Position { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_Title"></a>Title

Gets the title of the track.

```csharp
[JsonProperty("title")]
public string Title { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_TrackString"></a>TrackString

Gets or sets the ID of the track to play.

```csharp
[JsonIgnore]
public string TrackString { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkTrack_Uri"></a>Uri

Gets the source Uri of this track.

```csharp
[JsonProperty("uri")]
public Uri Uri { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

