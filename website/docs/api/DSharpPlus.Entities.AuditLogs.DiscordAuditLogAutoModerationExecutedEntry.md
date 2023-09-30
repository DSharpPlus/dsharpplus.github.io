# Class DiscordAuditLogAutoModerationExecutedEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogAutoModerationExecutedEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogAutoModerationExecutedEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogAutoModerationExecutedEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationExecutedEntry_Channel"></a>Channel

Channel where the rule was executed

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationExecutedEntry_ResponsibleRule"></a>ResponsibleRule

Name of the rule that was executed

```csharp
public string ResponsibleRule { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationExecutedEntry_RuleTriggerType"></a>RuleTriggerType

Type of the trigger that was executed

```csharp
public RuleTriggerType RuleTriggerType { get; }
```

#### Property Value

[RuleTriggerType](DSharpPlus.Enums.RuleTriggerType.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationExecutedEntry_TargetUser"></a>TargetUser

User that was affected by the rule

```csharp
public DiscordUser TargetUser { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

