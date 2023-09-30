# Class DiscordThreadChannelMetadata

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public class DiscordThreadChannelMetadata
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordThreadChannelMetadata](DSharpPlus.Entities.DiscordThreadChannelMetadata.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordThreadChannelMetadata_ArchiveTimestamp"></a>ArchiveTimestamp

Gets the time timestamp for when the thread's archive status was last changed.

```csharp
[JsonProperty("archive_timestamp", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? ArchiveTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordThreadChannelMetadata_AutoArchiveDuration"></a>AutoArchiveDuration

Gets the duration in minutes to automatically archive the thread after recent activity. Can be set to: 60, 1440, 4320, 10080.

```csharp
[JsonProperty("auto_archive_duration", NullValueHandling = NullValueHandling.Ignore)]
public AutoArchiveDuration AutoArchiveDuration { get; }
```

#### Property Value

[AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

### <a id="DSharpPlus_Entities_DiscordThreadChannelMetadata_CreationTimestamp"></a>CreationTimestamp

Gets the time this thread was created. Only populated for threads created after 2022-01-09 (YYYY-MM-DD).

```csharp
public DateTimeOffset? CreationTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordThreadChannelMetadata_IsArchived"></a>IsArchived

Gets whether this thread is archived or not.

```csharp
[JsonProperty("archived", NullValueHandling = NullValueHandling.Ignore)]
public bool IsArchived { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordThreadChannelMetadata_IsLocked"></a>IsLocked

Gets whether this thread is locked or not.

```csharp
[JsonProperty("locked", NullValueHandling = NullValueHandling.Ignore)]
public bool? IsLocked { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

