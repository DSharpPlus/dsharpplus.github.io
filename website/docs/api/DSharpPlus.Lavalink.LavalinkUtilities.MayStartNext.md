# Method MayStartNext

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkUtilities_MayStartNext_DSharpPlus_Lavalink_EventArgs_TrackEndReason_"></a>MayStartNext\(TrackEndReason\)

Indicates whether a new track should be started after reciving this TrackEndReason. If this is false, either this event is
already triggered because another track started (REPLACED) or because the player is stopped (STOPPED, CLEANUP).

```csharp
public static bool MayStartNext(this TrackEndReason reason)
```

### Parameters

`reason` [TrackEndReason](DSharpPlus.Lavalink.EventArgs.TrackEndReason.md)

### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

