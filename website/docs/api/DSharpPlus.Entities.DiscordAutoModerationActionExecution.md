# Class DiscordAutoModerationActionExecution

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord rule executed action.

```csharp
public class DiscordAutoModerationActionExecution
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordAutoModerationActionExecution](DSharpPlus.Entities.DiscordAutoModerationActionExecution.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_Action"></a>Action

Gets the action which was executed.

```csharp
[JsonProperty("action")]
public DiscordAutoModerationAction? Action { get; }
```

#### Property Value

[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_AlertSystemMessageId"></a>AlertSystemMessageId

Gets the id of the message sent by the alert system.

```csharp
[JsonProperty("alert_system_message_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? AlertSystemMessageId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_ChannelId"></a>ChannelId

Gets the id of the channel in which user triggered the rule.

```csharp
[JsonProperty("channel_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_Content"></a>Content

Gets the content of the message.

```csharp
[JsonProperty("content", NullValueHandling = NullValueHandling.Ignore)]
public string? Content { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

#### Remarks

<xref href="DSharpPlus.DiscordIntents.MessageContents" data-throw-if-not-resolved="false"></xref> is required to not get an empty value.

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_GuildId"></a>GuildId

Gets the id of the guild in which action was executed.

```csharp
[JsonProperty("guild_id")]
public ulong GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_MatchedContent"></a>MatchedContent

Gets the substring in content that triggered the rule.

```csharp
[JsonProperty("matched_content", NullValueHandling = NullValueHandling.Ignore)]
public string? MatchedContent { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

#### Remarks

<xref href="DSharpPlus.DiscordIntents.MessageContents" data-throw-if-not-resolved="false"></xref> is required to not get an empty value.

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_MatchedKeyword"></a>MatchedKeyword

Gets the keywords (word or phrase) configured in the rule that triggered it.

```csharp
[JsonProperty("matched_keyword")]
public string? MatchedKeyword { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_MessageId"></a>MessageId

Gets the id of any user message which content belongs to.

```csharp
[JsonProperty("message_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? MessageId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_RuleId"></a>RuleId

Gets the id of the rule which was triggered.

```csharp
[JsonProperty("rule_id")]
public ulong RuleId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_TriggerType"></a>TriggerType

Gets the rule trigger type.

```csharp
[JsonProperty("rule_trigger_type")]
public RuleTriggerType TriggerType { get; }
```

#### Property Value

[RuleTriggerType](DSharpPlus.Enums.RuleTriggerType.md)

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionExecution_UserId"></a>UserId

Gets the id of the user which triggered the rule.

```csharp
[JsonProperty("user_id")]
public ulong UserId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

