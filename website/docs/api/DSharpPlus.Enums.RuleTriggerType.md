# Enum RuleTriggerType

Namespace: [DSharpPlus.Enums](DSharpPlus.Enums.md)  
Assembly: DSharpPlus.dll

Characterizes the type of content which can trigger a rule.

```csharp
public enum RuleTriggerType
```

###### Extension Methods

[ExtensionMethods.GetName<RuleTriggerType\>\(RuleTriggerType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`Keyword = 1` 

Check if the content contains words from a definied list of keywords.

`KeywordPreset = 4` 

Check if the content contains words from pre-defined wordsets.

`MentionSpam = 5` 

Check if the content contains moure unique mentions than allowed.

`Spam = 3` 

Check if the content is a spam.

