# Method GetAutoModerationRuleAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetAutoModerationRuleAsync_System_UInt64_"></a>GetAutoModerationRuleAsync\(ulong\)

Gets an auto-moderation rule by an id.

```csharp
public Task<DiscordAutoModerationRule> GetAutoModerationRuleAsync(ulong ruleId)
```

### Parameters

`ruleId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The rule id.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The found rule.

