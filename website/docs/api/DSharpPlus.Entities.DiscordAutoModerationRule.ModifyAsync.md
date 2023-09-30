# Method ModifyAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordAutoModerationRule_ModifyAsync_System_Action_DSharpPlus_Net_Models_AutoModerationRuleEditModel__"></a>ModifyAsync\(Action<AutoModerationRuleEditModel\>\)

Modify the rule in the guild.

```csharp
public Task<DiscordAutoModerationRule> ModifyAsync(Action<AutoModerationRuleEditModel> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[AutoModerationRuleEditModel](DSharpPlus.Net.Models.AutoModerationRuleEditModel.md)\>

Action the perform on this rule.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The modified rule.

