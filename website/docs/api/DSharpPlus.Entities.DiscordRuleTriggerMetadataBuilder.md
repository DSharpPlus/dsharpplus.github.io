# Class DiscordRuleTriggerMetadataBuilder

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordRuleTriggerMetadataBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordRuleTriggerMetadataBuilder](DSharpPlus.Entities.DiscordRuleTriggerMetadataBuilder.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_AllowedKeywords"></a>AllowedKeywords

Sets the substrings which should not trigger the rule.

```csharp
public IReadOnlyList<string>? AllowedKeywords { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_KeywordFilter"></a>KeywordFilter

Sets substrings which will be searched in the content.

```csharp
public IReadOnlyList<string>? KeywordFilter { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_KeywordPresetTypes"></a>KeywordPresetTypes

Sets the internally pre-defined wordsets which will be searched in the content.

```csharp
public IReadOnlyList<RuleKeywordPresetType>? KeywordPresetTypes { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[RuleKeywordPresetType](DSharpPlus.Enums.RuleKeywordPresetType.md)\>?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_MentionTotalLimit"></a>MentionTotalLimit

Sets the total number of mentions (users and roles) allowed per message.

```csharp
public int? MentionTotalLimit { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_RegexPatterns"></a>RegexPatterns

Sets regex patterns which will be matched against the content.

```csharp
public IReadOnlyList<string>? RegexPatterns { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>?

## Methods

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_AddAllowedKeywordList_System_Collections_Generic_IReadOnlyList_System_String__"></a>AddAllowedKeywordList\(IReadOnlyList<string\>\)

Sets an allowed keyword list.

```csharp
public DiscordRuleTriggerMetadataBuilder AddAllowedKeywordList(IReadOnlyList<string> allowList)
```

#### Parameters

`allowList` [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

The keyword list to set.

#### Returns

[DiscordRuleTriggerMetadataBuilder](DSharpPlus.Entities.DiscordRuleTriggerMetadataBuilder.md)

This builder.

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_AddKeywordFilter_System_Collections_Generic_IReadOnlyList_System_String__"></a>AddKeywordFilter\(IReadOnlyList<string\>\)

Sets keywords that will be searched in messages content.

```csharp
public DiscordRuleTriggerMetadataBuilder AddKeywordFilter(IReadOnlyList<string> keywordFilter)
```

#### Parameters

`keywordFilter` [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

The keywords that will be searched.

#### Returns

[DiscordRuleTriggerMetadataBuilder](DSharpPlus.Entities.DiscordRuleTriggerMetadataBuilder.md)

This builder.

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_AddKeywordPresetTypes_System_Collections_Generic_IReadOnlyList_DSharpPlus_Enums_RuleKeywordPresetType__"></a>AddKeywordPresetTypes\(IReadOnlyList<RuleKeywordPresetType\>\)

Sets the rule keyword preset types.

```csharp
public DiscordRuleTriggerMetadataBuilder AddKeywordPresetTypes(IReadOnlyList<RuleKeywordPresetType> keywordPresetTypes)
```

#### Parameters

`keywordPresetTypes` [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[RuleKeywordPresetType](DSharpPlus.Enums.RuleKeywordPresetType.md)\>

The rule keyword preset types to set.

#### Returns

[DiscordRuleTriggerMetadataBuilder](DSharpPlus.Entities.DiscordRuleTriggerMetadataBuilder.md)

This builder.

#### Exceptions

[ArgumentNullException](https://learn.microsoft.com/dotnet/api/system.argumentnullexception)

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_AddRegexPatterns_System_Collections_Generic_IReadOnlyList_System_String__"></a>AddRegexPatterns\(IReadOnlyList<string\>\)

Sets the regex patterns.

```csharp
public DiscordRuleTriggerMetadataBuilder AddRegexPatterns(IReadOnlyList<string> regexPatterns)
```

#### Parameters

`regexPatterns` [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

#### Returns

[DiscordRuleTriggerMetadataBuilder](DSharpPlus.Entities.DiscordRuleTriggerMetadataBuilder.md)

This builder.

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_Build"></a>Build\(\)

Constructs a new trigger rule metadata.

```csharp
public DiscordRuleTriggerMetadata Build()
```

#### Returns

[DiscordRuleTriggerMetadata](DSharpPlus.Entities.DiscordRuleTriggerMetadata.md)

The build trigger metadata.

### <a id="DSharpPlus_Entities_DiscordRuleTriggerMetadataBuilder_WithMentionTotalLimit_System_Nullable_System_Int32__"></a>WithMentionTotalLimit\(int?\)

Sets the total mention limit.

```csharp
public DiscordRuleTriggerMetadataBuilder WithMentionTotalLimit(int? mentionTotalLimit)
```

#### Parameters

`mentionTotalLimit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The total mention limit number.

#### Returns

[DiscordRuleTriggerMetadataBuilder](DSharpPlus.Entities.DiscordRuleTriggerMetadataBuilder.md)

This builder.

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

