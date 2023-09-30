# Class DiscordAuditLogGuildEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogGuildEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogGuildEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogGuildEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_AfkChannelChange"></a>AfkChannelChange

Gets the description of afk channel's change.

```csharp
public PropertyChange<DiscordChannel?> AfkChannelChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_EmbedChannelChange"></a>EmbedChannelChange

Gets the description of widget channel's change.

```csharp
public PropertyChange<DiscordChannel?> EmbedChannelChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_ExplicitContentFilterChange"></a>ExplicitContentFilterChange

Gets the description of explicit content filter settings' change.

```csharp
public PropertyChange<ExplicitContentFilter?> ExplicitContentFilterChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ExplicitContentFilter](DSharpPlus.Entities.ExplicitContentFilter.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_IconChange"></a>IconChange

Gets the description of icon's change.

```csharp
public PropertyChange<string?> IconChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_MfaLevelChange"></a>MfaLevelChange

Gets the description of guild's mfa level change.

```csharp
public PropertyChange<MfaLevel?> MfaLevelChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[MfaLevel](DSharpPlus.Entities.MfaLevel.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_NameChange"></a>NameChange

Gets the description of guild name's change.

```csharp
public PropertyChange<string?> NameChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_NotificationSettingsChange"></a>NotificationSettingsChange

Gets the description of notification settings' change.

```csharp
public PropertyChange<DefaultMessageNotifications?> NotificationSettingsChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_OwnerChange"></a>OwnerChange

Gets the description of owner's change.

```csharp
public PropertyChange<DiscordMember?> OwnerChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_RegionChange"></a>RegionChange

Gets the description of the guild's region change.

```csharp
public PropertyChange<string?> RegionChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_SplashChange"></a>SplashChange

Gets the description of invite splash's change.

```csharp
public PropertyChange<string?> SplashChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_SystemChannelChange"></a>SystemChannelChange

Gets the description of system message channel's change.

```csharp
public PropertyChange<DiscordChannel?> SystemChannelChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_Target"></a>Target

Gets the affected guild.

```csharp
public DiscordGuild Target { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogGuildEntry_VerificationLevelChange"></a>VerificationLevelChange

Gets the description of verification level's change.

```csharp
public PropertyChange<VerificationLevel?> VerificationLevelChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)?\>

