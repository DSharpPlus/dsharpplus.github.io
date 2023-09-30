# Method CreateAutoModerationRuleAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateAutoModerationRuleAsync_System_String_DSharpPlus_Enums_RuleEventType_DSharpPlus_Enums_RuleTriggerType_DSharpPlus_Entities_DiscordRuleTriggerMetadata_System_Collections_Generic_IReadOnlyList_DSharpPlus_Entities_DiscordAutoModerationAction__DSharpPlus_Entities_Optional_System_Boolean__DSharpPlus_Entities_Optional_System_Collections_Generic_IReadOnlyList_DSharpPlus_Entities_DiscordRole___DSharpPlus_Entities_Optional_System_Collections_Generic_IReadOnlyList_DSharpPlus_Entities_DiscordChannel___System_String_"></a>CreateAutoModerationRuleAsync\(string, RuleEventType, RuleTriggerType, DiscordRuleTriggerMetadata, IReadOnlyList<DiscordAutoModerationAction\>, Optional<bool\>, Optional<IReadOnlyList<DiscordRole\>\>, Optional<IReadOnlyList<DiscordChannel\>\>, string\)

Creates an auto-moderation rule in the guild.

```csharp
public Task<DiscordAutoModerationRule> CreateAutoModerationRuleAsync(string name, RuleEventType eventType, RuleTriggerType triggerType, DiscordRuleTriggerMetadata triggerMetadata, IReadOnlyList<DiscordAutoModerationAction> actions, Optional<bool> enabled = default, Optional<IReadOnlyList<DiscordRole>> exemptRoles = default, Optional<IReadOnlyList<DiscordChannel>> exemptChannels = default, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The rule name.

`eventType` [RuleEventType](DSharpPlus.Enums.RuleEventType.md)

The event in which the rule should be triggered.

`triggerType` [RuleTriggerType](DSharpPlus.Enums.RuleTriggerType.md)

The type of content which can trigger the rule.

`triggerMetadata` [DiscordRuleTriggerMetadata](DSharpPlus.Entities.DiscordRuleTriggerMetadata.md)

Metadata used to determine whether a rule should be triggered. This argument can be skipped depending eventType value.

`actions` [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)\>

Actions that will execute after the trigger of the rule.

`enabled` [Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the rule is enabled or not.

`exemptRoles` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>\>

Roles that will not trigger the rule.

`exemptChannels` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>\>

Channels which will not trigger the rule.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The created rule.

