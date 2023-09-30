# Class DiscordAuditLogRoleUpdateEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogRoleUpdateEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogRoleUpdateEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogRoleUpdateEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogRoleUpdateEntry_ColorChange"></a>ColorChange

Gets the description of role's color change.

```csharp
public PropertyChange<int?> ColorChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogRoleUpdateEntry_HoistChange"></a>HoistChange

Gets the description of the role's hoist status change.

```csharp
public PropertyChange<bool?> HoistChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogRoleUpdateEntry_MentionableChange"></a>MentionableChange

Gets the description of the role's mentionability change.

```csharp
public PropertyChange<bool?> MentionableChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogRoleUpdateEntry_NameChange"></a>NameChange

Gets the description of role's name change.

```csharp
public PropertyChange<string> NameChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogRoleUpdateEntry_PermissionChange"></a>PermissionChange

Gets the description of role's permission set change.

```csharp
public PropertyChange<Permissions?> PermissionChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[Permissions](DSharpPlus.Permissions.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogRoleUpdateEntry_PositionChange"></a>PositionChange

Gets the description of the role's position change.

```csharp
public PropertyChange<int?> PositionChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogRoleUpdateEntry_Target"></a>Target

Gets the affected role.

```csharp
public DiscordRole Target { get; }
```

#### Property Value

[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

