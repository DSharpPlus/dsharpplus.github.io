# Class DiscordAuditLogStickerEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogStickerEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogStickerEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogStickerEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_AssetChange"></a>AssetChange

Gets the description of sticker's tags change.

```csharp
public PropertyChange<string> AssetChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_AvailabilityChange"></a>AvailabilityChange

Gets the description of sticker's availability change.

```csharp
public PropertyChange<bool?> AvailabilityChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_DescriptionChange"></a>DescriptionChange

Gets the description of sticker's description change.

```csharp
public PropertyChange<string> DescriptionChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_FormatChange"></a>FormatChange

Gets the description of sticker's format change.

```csharp
public PropertyChange<StickerFormat?> FormatChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[StickerFormat](DSharpPlus.Entities.StickerFormat.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_GuildIdChange"></a>GuildIdChange

Gets the description of sticker's guild id change.

```csharp
public PropertyChange<ulong?> GuildIdChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_IdChange"></a>IdChange

Gets the description of sticker's id change.

```csharp
public PropertyChange<ulong?> IdChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_NameChange"></a>NameChange

Gets the description of sticker's name change.

```csharp
public PropertyChange<string> NameChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_TagsChange"></a>TagsChange

Gets the description of sticker's tags change.

```csharp
public PropertyChange<string> TagsChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_Target"></a>Target

Gets the affected sticker.

```csharp
public DiscordMessageSticker Target { get; }
```

#### Property Value

[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogStickerEntry_TypeChange"></a>TypeChange

Gets the description of sticker's type change.

```csharp
public PropertyChange<StickerType?> TypeChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[StickerType](DSharpPlus.Entities.StickerType.md)?\>

