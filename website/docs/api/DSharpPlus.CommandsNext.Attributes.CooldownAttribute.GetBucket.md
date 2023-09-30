# Method GetBucket

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Attributes_CooldownAttribute_GetBucket_DSharpPlus_CommandsNext_CommandContext_"></a>GetBucket\(CommandContext\)

Gets a cooldown bucket for given command context.

```csharp
public CommandCooldownBucket GetBucket(CommandContext ctx)
```

### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Command context to get cooldown bucket for.

### Returns

[CommandCooldownBucket](DSharpPlus.CommandsNext.Attributes.CommandCooldownBucket.md)

Requested cooldown bucket, or null if one wasn't present.

