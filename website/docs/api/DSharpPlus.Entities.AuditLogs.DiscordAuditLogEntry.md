# Class DiscordAuditLogEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

Represents an audit log entry.

```csharp
public abstract class DiscordAuditLogEntry : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md)

###### Derived

[DiscordAuditLogApplicationCommandPermissionEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogApplicationCommandPermissionEntry.md), 
[DiscordAuditLogAutoModerationExecutedEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogAutoModerationExecutedEntry.md), 
[DiscordAuditLogAutoModerationRuleEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogAutoModerationRuleEntry.md), 
[DiscordAuditLogBanEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogBanEntry.md), 
[DiscordAuditLogBotAddEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogBotAddEntry.md), 
[DiscordAuditLogChannelEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogChannelEntry.md), 
[DiscordAuditLogEmojiEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEmojiEntry.md), 
[DiscordAuditLogGuildEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogGuildEntry.md), 
[DiscordAuditLogGuildScheduledEventEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogGuildScheduledEventEntry.md), 
[DiscordAuditLogIntegrationEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogIntegrationEntry.md), 
[DiscordAuditLogInviteEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogInviteEntry.md), 
[DiscordAuditLogKickEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogKickEntry.md), 
[DiscordAuditLogMemberDisconnectEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogMemberDisconnectEntry.md), 
[DiscordAuditLogMemberMoveEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogMemberMoveEntry.md), 
[DiscordAuditLogMemberUpdateEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogMemberUpdateEntry.md), 
[DiscordAuditLogMessageEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogMessageEntry.md), 
[DiscordAuditLogMessagePinEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogMessagePinEntry.md), 
[DiscordAuditLogOverwriteEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogOverwriteEntry.md), 
[DiscordAuditLogPruneEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogPruneEntry.md), 
[DiscordAuditLogRoleUpdateEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogRoleUpdateEntry.md), 
[DiscordAuditLogStickerEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogStickerEntry.md), 
[DiscordAuditLogThreadEventEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogThreadEventEntry.md), 
[DiscordAuditLogWebhookEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogWebhookEntry.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogEntry_ActionCategory"></a>ActionCategory

Gets the category under which the action falls.

```csharp
public AuditLogActionCategory ActionCategory { get; }
```

#### Property Value

[AuditLogActionCategory](DSharpPlus.Entities.AuditLogs.AuditLogActionCategory.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogEntry_ActionType"></a>ActionType

Gets the entry's action type.

```csharp
public AuditLogActionType ActionType { get; }
```

#### Property Value

[AuditLogActionType](DSharpPlus.Entities.AuditLogs.AuditLogActionType.md)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogEntry_Reason"></a>Reason

Gets the reason defined in the action.

```csharp
public string Reason { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogEntry_UserResponsible"></a>UserResponsible

Gets the user responsible for the action.

```csharp
public DiscordUser UserResponsible { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

