# Class DiscordAutoModerationActionBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Constructs auto-moderation actions.

```csharp
public class DiscordAutoModerationActionBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordAutoModerationActionBuilder](DSharpPlus.Entities.DiscordAutoModerationActionBuilder.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionBuilder_Metadata"></a>Metadata

Sets additional metadata needed during execution for this specific action type.

```csharp
public DiscordRuleActionMetadata? Metadata { get; }
```

#### Property Value

[DiscordRuleActionMetadata](DSharpPlus.Entities.DiscordRuleActionMetadata.md)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionBuilder_Type"></a>Type

Sets the rule action type.

```csharp
public RuleActionType Type { get; }
```

#### Property Value

[RuleActionType](DSharpPlus.Enums.RuleActionType.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionBuilder_Build"></a>Build\(\)

Constructs a new trigger rule action.

```csharp
public DiscordAutoModerationAction Build()
```

#### Returns

[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)

The built rule.

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionBuilder_WithActionMetadata_DSharpPlus_Entities_DiscordRuleActionMetadata_"></a>WithActionMetadata\(DiscordRuleActionMetadata\)

Sets the action metadata.

```csharp
public DiscordAutoModerationActionBuilder WithActionMetadata(DiscordRuleActionMetadata metadata)
```

#### Parameters

`metadata` [DiscordRuleActionMetadata](DSharpPlus.Entities.DiscordRuleActionMetadata.md)

The action metadata.

#### Returns

[DiscordAutoModerationActionBuilder](DSharpPlus.Entities.DiscordAutoModerationActionBuilder.md)

This builder.

### <a id="DSharpPlus_Entities_DiscordAutoModerationActionBuilder_WithRuleActionType_DSharpPlus_Enums_RuleActionType_"></a>WithRuleActionType\(RuleActionType\)

Sets the rule action type.

```csharp
public DiscordAutoModerationActionBuilder WithRuleActionType(RuleActionType type)
```

#### Parameters

`type` [RuleActionType](DSharpPlus.Enums.RuleActionType.md)

The rule action type.

#### Returns

[DiscordAutoModerationActionBuilder](DSharpPlus.Entities.DiscordAutoModerationActionBuilder.md)

This builder.

