# Enum LavalinkLoadResultType

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents Lavalink track loading results.

```csharp
[JsonConverter(typeof(StringEnumConverter))]
public enum LavalinkLoadResultType
```

###### Extension Methods

[ExtensionMethods.GetName<LavalinkLoadResultType\>\(LavalinkLoadResultType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`LoadFailed = 4` 

Specifies that the track failed to load.

`NoMatches = 3` 

Specifies that the search yielded no results.

`PlaylistLoaded = 1` 

Specifies that playlist was loaded successfully.

`SearchResult = 2` 

Specifies that the result set contains search results.

`TrackLoaded = 0` 

Specifies that track was loaded successfully.

