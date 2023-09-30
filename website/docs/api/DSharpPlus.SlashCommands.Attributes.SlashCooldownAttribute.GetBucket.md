# Method GetBucket

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_Attributes_SlashCooldownAttribute_GetBucket_DSharpPlus_SlashCommands_InteractionContext_"></a>GetBucket\(InteractionContext\)

Gets a cooldown bucket for given command context.

```csharp
public SlashCommandCooldownBucket GetBucket(InteractionContext ctx)
```

### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

Command context to get cooldown bucket for.

### Returns

[SlashCommandCooldownBucket](DSharpPlus.SlashCommands.Attributes.SlashCommandCooldownBucket.md)

Requested cooldown bucket, or null if one wasn't present.

