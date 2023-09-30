# Class DiscordAuditLogChannelEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogChannelEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogChannelEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogChannelEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_AvailableTags"></a>AvailableTags

```csharp
public PropertyChange<IEnumerable<DiscordForumTag>> AvailableTags { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md)\>\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_BitrateChange"></a>BitrateChange

Gets the description of channel's bitrate change.

```csharp
public PropertyChange<int?> BitrateChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_Flags"></a>Flags

```csharp
public PropertyChange<ChannelFlags?> Flags { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ChannelFlags](DSharpPlus.ChannelFlags.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_NameChange"></a>NameChange

Gets the description of channel's name change.

```csharp
public PropertyChange<string> NameChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_NsfwChange"></a>NsfwChange

Gets the description of channel's nsfw flag change.

```csharp
public PropertyChange<bool?> NsfwChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_OverwriteChange"></a>OverwriteChange

Gets the description of channel permission overwrites' change.

```csharp
public PropertyChange<IReadOnlyList<DiscordOverwrite>> OverwriteChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordOverwrite](DSharpPlus.Entities.DiscordOverwrite.md)\>\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_PerUserRateLimitChange"></a>PerUserRateLimitChange

Gets the description of channel's slow mode timeout change.

```csharp
public PropertyChange<int?> PerUserRateLimitChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_Target"></a>Target

Gets the affected channel.

```csharp
public DiscordChannel Target { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_TopicChange"></a>TopicChange

Gets the description of channel's topic change.

```csharp
public PropertyChange<string> TopicChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_TypeChange"></a>TypeChange

Gets the description of channel's type change.

```csharp
public PropertyChange<ChannelType?> TypeChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ChannelType](DSharpPlus.ChannelType.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogChannelEntry_UserLimit"></a>UserLimit

```csharp
public PropertyChange<int?> UserLimit { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

