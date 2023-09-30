# Class DiscordAuditLogMemberUpdateEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogMemberUpdateEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogMemberUpdateEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogMemberUpdateEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogMemberUpdateEntry_AddedRoles"></a>AddedRoles

Gets the roles that were added to the member.

```csharp
public IReadOnlyList<DiscordRole> AddedRoles { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogMemberUpdateEntry_DeafenChange"></a>DeafenChange

Gets the description of member's deaf status change.

```csharp
public PropertyChange<bool?> DeafenChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogMemberUpdateEntry_MuteChange"></a>MuteChange

Gets the description of member's mute status change.

```csharp
public PropertyChange<bool?> MuteChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogMemberUpdateEntry_NicknameChange"></a>NicknameChange

Gets the description of member's nickname change.

```csharp
public PropertyChange<string> NicknameChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogMemberUpdateEntry_RemovedRoles"></a>RemovedRoles

Gets the roles that were removed from the member.

```csharp
public IReadOnlyList<DiscordRole> RemovedRoles { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogMemberUpdateEntry_Target"></a>Target

Gets the affected member.

```csharp
public DiscordMember Target { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogMemberUpdateEntry_TimeoutChange"></a>TimeoutChange

Gets the change in a user's timeout status

```csharp
public PropertyChange<DateTime?> TimeoutChange { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DateTime](https://learn.microsoft.com/dotnet/api/system.datetime)?\>

