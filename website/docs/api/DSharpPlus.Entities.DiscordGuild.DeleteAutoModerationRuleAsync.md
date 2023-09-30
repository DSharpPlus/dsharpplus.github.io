# Method DeleteAutoModerationRuleAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_DeleteAutoModerationRuleAsync_System_UInt64_System_String_"></a>DeleteAutoModerationRuleAsync\(ulong, string\)

Deletes a auto-moderation rule by an id.

```csharp
public Task DeleteAutoModerationRuleAsync(ulong ruleId, string reason = null)
```

### Parameters

`ruleId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The rule id.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

