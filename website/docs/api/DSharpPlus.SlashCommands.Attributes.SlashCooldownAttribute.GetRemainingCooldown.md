# Method GetRemainingCooldown

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_GetRemainingCooldown_DSharpPlus_SlashCommands_InteractionContext_"></a>GetRemainingCooldown\(InteractionContext\)

Calculates the cooldown remaining for given command context.

```csharp
public TimeSpan GetRemainingCooldown(InteractionContext ctx)
```

### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

Context for which to calculate the cooldown.

### Returns

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

Remaining cooldown, or zero if no cooldown is active.

