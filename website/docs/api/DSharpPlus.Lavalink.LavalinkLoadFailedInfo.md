# Struct LavalinkLoadFailedInfo

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents properties sent when a Lavalink track is unable to load.

```csharp
public struct LavalinkLoadFailedInfo
```

## Properties

### <a id="DSharpPlus_Lavalink_LavalinkLoadFailedInfo_Message"></a>Message

Gets the message of the sent exception.

```csharp
[JsonProperty("message")]
public readonly string Message { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Lavalink_LavalinkLoadFailedInfo_Severity"></a>Severity

Gets the severity level of the track loading failure.

```csharp
[JsonProperty("severity")]
public readonly LoadFailedSeverity Severity { get; }
```

#### Property Value

[LoadFailedSeverity](DSharpPlus.Lavalink.LoadFailedSeverity.md)

