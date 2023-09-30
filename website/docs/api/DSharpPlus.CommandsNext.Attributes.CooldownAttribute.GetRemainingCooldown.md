# Method GetRemainingCooldown

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_GetRemainingCooldown_DSharpPlus_CommandsNext_CommandContext_"></a>GetRemainingCooldown\(CommandContext\)

Calculates the cooldown remaining for given command context.

```csharp
public TimeSpan GetRemainingCooldown(CommandContext ctx)
```

### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context for which to calculate the cooldown.

### Returns

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Remaining cooldown, or zero if no cooldown is active.

