# Class AutoModerationRuleEditModel

Namespace: [DSharpPlus.Net.Models](DSharpPlus.Net.Models.md)  
Assembly: DSharpPlus.dll

```csharp
public class AutoModerationRuleEditModel : BaseEditModel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseEditModel](DSharpPlus.Net.Models.BaseEditModel.md) ← 
[AutoModerationRuleEditModel](DSharpPlus.Net.Models.AutoModerationRuleEditModel.md)

###### Inherited Members

[BaseEditModel.AuditLogReason](DSharpPlus.Net.Models.BaseEditModel.md\#DSharpPlus\_Net\_Models\_BaseEditModel\_AuditLogReason)

## Properties

### <a id="DSharpPlus_Net_Models_AutoModerationRuleEditModel_Actions"></a>Actions

The new rule actions.

```csharp
public Optional<IReadOnlyList<DiscordAutoModerationAction>> Actions { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)\>\>

### <a id="DSharpPlus_Net_Models_AutoModerationRuleEditModel_Enable"></a>Enable

The new rule status.

```csharp
public Optional<bool> Enable { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

### <a id="DSharpPlus_Net_Models_AutoModerationRuleEditModel_EventType"></a>EventType

The new rule event type.

```csharp
public Optional<RuleEventType> EventType { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[RuleEventType](DSharpPlus.Enums.RuleEventType.md)\>

### <a id="DSharpPlus_Net_Models_AutoModerationRuleEditModel_ExemptChannels"></a>ExemptChannels

The new rule exempt channels.

```csharp
public Optional<IReadOnlyList<DiscordChannel>> ExemptChannels { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>\>

### <a id="DSharpPlus_Net_Models_AutoModerationRuleEditModel_ExemptRoles"></a>ExemptRoles

The new rule exempt roles.

```csharp
public Optional<IReadOnlyList<DiscordRole>> ExemptRoles { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>\>

### <a id="DSharpPlus_Net_Models_AutoModerationRuleEditModel_Name"></a>Name

The new rule name.

```csharp
public Optional<string> Name { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Net_Models_AutoModerationRuleEditModel_TriggerMetadata"></a>TriggerMetadata

The new rule trigger metadata.

```csharp
public Optional<DiscordRuleTriggerMetadata> TriggerMetadata { set; }
```

#### Property Value

[Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordRuleTriggerMetadata](DSharpPlus.Entities.DiscordRuleTriggerMetadata.md)\>

