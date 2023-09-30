# Class DiscordAutoModerationAction

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord auto moderation action.

```csharp
public class DiscordAutoModerationAction
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordAutoModerationAction_Metadata"></a>Metadata

Gets additional metadata needed during execution for this specific action type.

```csharp
[JsonProperty("metadata", NullValueHandling = NullValueHandling.Ignore)]
public DiscordRuleActionMetadata? Metadata { get; }
```

#### Property Value

[DiscordRuleActionMetadata](DSharpPlus.Entities.DiscordRuleActionMetadata.md)?

### <a id="DSharpPlus_Entities_DiscordAutoModerationAction_Type"></a>Type

Gets the rule action type.

```csharp
[JsonProperty("type")]
public RuleActionType Type { get; }
```

#### Property Value

[RuleActionType](DSharpPlus.Enums.RuleActionType.md)

