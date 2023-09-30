# Class DiscordAutoModerationRule

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord auto-moderation rule.

```csharp
public class DiscordAutoModerationRule : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_Actions"></a>Actions

Gets actions which will execute when the rule is triggered.

```csharp
[JsonProperty("actions")]
public IReadOnlyList<DiscordAutoModerationAction>? Actions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)\>?

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_Creator"></a>Creator

Gets the user that created the rule.

```csharp
[JsonIgnore]
public DiscordUser? Creator { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_EventType"></a>EventType

Gets the rule event type.

```csharp
[JsonProperty("event_type")]
public RuleEventType EventType { get; }
```

#### Property Value

[RuleEventType](DSharpPlus.Enums.RuleEventType.md)

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_ExemptChannels"></a>ExemptChannels

Gets ids of channels in which rule will be not triggered.

```csharp
[JsonProperty("exempt_channels", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<ulong>? ExemptChannels { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>?

#### Remarks

Maximum of 50.

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_ExemptRoles"></a>ExemptRoles

Gets ids of roles that will not trigger the rule.

```csharp
[JsonProperty("exempt_roles", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<ulong>? ExemptRoles { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>?

#### Remarks

Maximum of 20.

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_Guild"></a>Guild

Gets the guild which the rule is in.

```csharp
[JsonIgnore]
public DiscordGuild? Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_IsEnabled"></a>IsEnabled

Gets whether the rule is enabled.

```csharp
[JsonProperty("enabled", NullValueHandling = NullValueHandling.Ignore)]
public bool IsEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_Metadata"></a>Metadata

Gets the additional data to determine whether a rule should be triggered.

```csharp
[JsonProperty("trigger_metadata")]
public DiscordRuleTriggerMetadata? Metadata { get; }
```

#### Property Value

[DiscordRuleTriggerMetadata](DSharpPlus.Entities.DiscordRuleTriggerMetadata.md)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_Name"></a>Name

Gets the rule name.

```csharp
[JsonProperty("name")]
public string? Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_TriggerType"></a>TriggerType

Gets the rule trigger type.

```csharp
[JsonProperty("trigger_type")]
public RuleTriggerType TriggerType { get; }
```

#### Property Value

[RuleTriggerType](DSharpPlus.Enums.RuleTriggerType.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_DeleteAsync_System_String_"></a>DeleteAsync\(string\)

Deletes the rule in the guild.

```csharp
public Task DeleteAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audits logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordAutoModerationRule_ModifyAsync_System_Action_DSharpPlus_Net_Models_AutoModerationRuleEditModel__"></a>ModifyAsync\(Action<AutoModerationRuleEditModel\>\)

Modify the rule in the guild.

```csharp
public Task<DiscordAutoModerationRule> ModifyAsync(Action<AutoModerationRuleEditModel> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[AutoModerationRuleEditModel](DSharpPlus.Net.Models.AutoModerationRuleEditModel.md)\>

Action the perform on this rule.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The modified rule.

