# Class DiscordRuleTriggerMetadata

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents metadata about the triggering of a Discord rule.

```csharp
public sealed class DiscordRuleTriggerMetadata
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordRuleTriggerMetadata](DSharpPlus.Entities.DiscordRuleTriggerMetadata.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadata_AllowedKeywords"></a>AllowedKeywords

Gets the substrings which should not trigger the rule.

```csharp
[JsonProperty("allow_list")]
public IReadOnlyList<string>? AllowedKeywords { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadata_KeywordFilter"></a>KeywordFilter

Gets substrings which will be searched in the content.

```csharp
[JsonProperty("keyword_filter", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<string>? KeywordFilter { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadata_KeywordPresetTypes"></a>KeywordPresetTypes

Gets the internally pre-defined wordsets which will be searched in the content.

```csharp
[JsonProperty("presets", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<RuleKeywordPresetType>? KeywordPresetTypes { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[RuleKeywordPresetType](DSharpPlus.Enums.RuleKeywordPresetType.md)\>?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadata_MentionTotalLimit"></a>MentionTotalLimit

Gets the total number of mentions (users and roles) allowed per message.

```csharp
[JsonProperty("mention_total_limit", NullValueHandling = NullValueHandling.Ignore)]
public int? MentionTotalLimit { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadata_RegexPatterns"></a>RegexPatterns

Gets regex patterns which will be matched against the content.

```csharp
[JsonProperty("regex_patterns")]
public IReadOnlyList<string>? RegexPatterns { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

