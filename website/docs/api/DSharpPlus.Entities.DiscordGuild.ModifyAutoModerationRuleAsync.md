# Method ModifyAutoModerationRuleAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyAutoModerationRuleAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_AutoModerationRuleEditModel__"></a>ModifyAutoModerationRuleAsync\(ulong, Action<AutoModerationRuleEditModel\>\)

Modify an auto-moderation rule in the guild.

```csharp
public Task<DiscordAutoModerationRule> ModifyAutoModerationRuleAsync(ulong ruleId, Action<AutoModerationRuleEditModel> action)
```

### Parameters

`ruleId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the rule that will be edited.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[AutoModerationRuleEditModel](DSharpPlus.Net.Models.AutoModerationRuleEditModel.md)\>

Action to perform on this rule.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The modified rule.

### Remarks

All arguments are optionals.

