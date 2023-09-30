# Class DiscordAuditLogOverwriteEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogOverwriteEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogOverwriteEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogOverwriteEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogOverwriteEntry_AllowedPermissions"></a>AllowedPermissions

Gets the description of overwrite's allow value change.

```csharp
public PropertyChange<Permissions?> AllowedPermissions { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[Permissions](DSharpPlus.Permissions.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogOverwriteEntry_Channel"></a>Channel

Gets the channel for which the overwrite was changed.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogOverwriteEntry_DeniedPermissions"></a>DeniedPermissions

Gets the description of overwrite's deny value change.

```csharp
public PropertyChange<Permissions?> DeniedPermissions { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[Permissions](DSharpPlus.Permissions.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogOverwriteEntry_Target"></a>Target

Gets the affected overwrite.

```csharp
public DiscordOverwrite Target { get; }
```

#### Property Value

[DiscordOverwrite](DSharpPlus.Entities.DiscordOverwrite.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogOverwriteEntry_TargetIdChange"></a>TargetIdChange

Gets the description of overwrite's target id change.

```csharp
public PropertyChange<ulong?> TargetIdChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogOverwriteEntry_Type"></a>Type

Gets the description of overwrite's type change.

```csharp
public PropertyChange<OverwriteType> Type { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[OverwriteType](DSharpPlus.OverwriteType.md)\>

