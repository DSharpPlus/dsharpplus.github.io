# Class LavalinkUtilities

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Various utilities for Lavalink.

```csharp
public static class LavalinkUtilities
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[LavalinkUtilities](DSharpPlus.Lavalink.LavalinkUtilities.md)

## Methods

### <a id="DSharpPlus_Lavalink_LavalinkUtilities_DecodeTrack_System_String_"></a>DecodeTrack\(string\)

Decodes a Lavalink track string.

```csharp
public static LavalinkTrack DecodeTrack(string track)
```

#### Parameters

`track` [string](https://learn.microsoft.com/dotnet/api/system.string)

Track string to decode.

#### Returns

[LavalinkTrack](DSharpPlus.Lavalink.LavalinkTrack.md)

Decoded Lavalink track.

### <a id="DSharpPlus_Lavalink_LavalinkUtilities_MayStartNext_DSharpPlus_Lavalink_EventArgs_TrackEndReason_"></a>MayStartNext\(TrackEndReason\)

Indicates whether a new track should be started after reciving this TrackEndReason. If this is false, either this event is
already triggered because another track started (REPLACED) or because the player is stopped (STOPPED, CLEANUP).

```csharp
public static bool MayStartNext(this TrackEndReason reason)
```

#### Parameters

`reason` [TrackEndReason](DSharpPlus.Lavalink.EventArgs.TrackEndReason.md)

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

