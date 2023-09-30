# Class DiscordAuditLogAutoModerationRuleEntry

Namespace: [DSharpPlus.Entities.AuditLogs](DSharpPlus.Entities.AuditLogs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordAuditLogAutoModerationRuleEntry : DiscordAuditLogEntry
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md) ← 
[DiscordAuditLogAutoModerationRuleEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogAutoModerationRuleEntry.md)

###### Inherited Members

[DiscordAuditLogEntry.ActionType](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionType), 
[DiscordAuditLogEntry.UserResponsible](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_UserResponsible), 
[DiscordAuditLogEntry.Reason](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_Reason), 
[DiscordAuditLogEntry.ActionCategory](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md\#DSharpPlus\_Entities\_AuditLogs\_DiscordAuditLogEntry\_ActionCategory), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_Actions"></a>Actions

Actions which will execute when the rule is triggered.

```csharp
public PropertyChange<IEnumerable<DiscordAutoModerationAction>?> Actions { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)\>?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_AddedAllowList"></a>AddedAllowList

List of strings that were added to the allow list

```csharp
public IEnumerable<string>? AddedAllowList { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_AddedKeywords"></a>AddedKeywords

List of trigger keywords that were added to the rule

```csharp
public IEnumerable<string>? AddedKeywords { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_AddedRegexPatterns"></a>AddedRegexPatterns

List of trigger regex patterns that were added to the rule

```csharp
public IEnumerable<string>? AddedRegexPatterns { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_CreatorId"></a>CreatorId

Id of the user that created the rule

```csharp
public PropertyChange<ulong?> CreatorId { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_Enabled"></a>Enabled

Whether the rule is enabled or not.

```csharp
public PropertyChange<bool?> Enabled { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_EventType"></a>EventType

Indicates in what event context a rule should be checked.

```csharp
public PropertyChange<RuleEventType?> EventType { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[RuleEventType](DSharpPlus.Enums.RuleEventType.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_ExemptChannels"></a>ExemptChannels

Channels that should not be affected by the rule

```csharp
public PropertyChange<IEnumerable<DiscordChannel>?> ExemptChannels { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_ExemptRoles"></a>ExemptRoles

Roles that should not be affected by the rule

```csharp
public PropertyChange<IEnumerable<DiscordRole>?> ExemptRoles { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_GuildId"></a>GuildId

Id of the guild where the rule was changed

```csharp
public PropertyChange<ulong?> GuildId { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_Name"></a>Name

Name of the rule

```csharp
public PropertyChange<string?> Name { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_RemovedAllowList"></a>RemovedAllowList

List of strings that were removed from the allow list

```csharp
public IEnumerable<string>? RemovedAllowList { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_RemovedKeywords"></a>RemovedKeywords

List of trigger keywords that were removed from the rule

```csharp
public IEnumerable<string>? RemovedKeywords { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_RemovedRegexPatterns"></a>RemovedRegexPatterns

List of trigger regex patterns that were removed from the rule

```csharp
public IEnumerable<string>? RemovedRegexPatterns { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_RuleId"></a>RuleId

Id of the rule

```csharp
public PropertyChange<ulong?> RuleId { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_TriggerMetadata"></a>TriggerMetadata

Additional data used to determine whether a rule should be triggered.

```csharp
public PropertyChange<DiscordRuleTriggerMetadata?> TriggerMetadata { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[DiscordRuleTriggerMetadata](DSharpPlus.Entities.DiscordRuleTriggerMetadata.md)?\>

### <a id="DSharpPlus_Entities_AuditLogs_DiscordAuditLogAutoModerationRuleEntry_TriggerType"></a>TriggerType

Characterizes the type of content which can trigger the rule.

```csharp
public PropertyChange<RuleTriggerType?> TriggerType { get; }
```

#### Property Value

[PropertyChange](DSharpPlus.Entities.AuditLogs.PropertyChange\-1.md)<[RuleTriggerType](DSharpPlus.Enums.RuleTriggerType.md)?\>

