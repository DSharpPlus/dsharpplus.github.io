# Enum LoadFailedSeverity

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

Represents severity level of the track loading failure.

```csharp
public enum LoadFailedSeverity
```

###### Extension Methods

[ExtensionMethods.GetName<LoadFailedSeverity\>\(LoadFailedSeverity\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Common = 0` 

Indicates a known cause for the failure, and not because of Lavaplayer.

`Fault = 2` 

Indicates an issue with Lavaplayer or otherwise no other way to determine the cause.

`Suspicious = 1` 

Indicates an unknown cause for the failure, most likely caused by outside sources.

