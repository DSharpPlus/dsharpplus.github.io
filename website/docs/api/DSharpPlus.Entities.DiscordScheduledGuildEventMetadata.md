# Class DiscordScheduledGuildEventMetadata

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Metadata for a <xref href="DSharpPlus.Entities.DiscordScheduledGuildEvent" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordScheduledGuildEventMetadata
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordScheduledGuildEventMetadata](DSharpPlus.Entities.DiscordScheduledGuildEventMetadata.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEventMetadata__ctor_System_String_"></a>DiscordScheduledGuildEventMetadata\(string\)

```csharp
public DiscordScheduledGuildEventMetadata(string location)
```

#### Parameters

`location` [string](https://learn.microsoft.com/dotnet/api/system.string)

## Properties

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEventMetadata_Location"></a>Location

If this is an external event, where this event is hosted.

```csharp
[JsonProperty("location")]
public string Location { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

