# Enum RuleActionType

Namespace: [DSharpPlus.Enums](DSharpPlus.Enums.md)  
Assembly: DSharpPlus.dll

Contains all actions that can be taken after a rule activation.

```csharp
public enum RuleActionType
```

###### Extension Methods

[ExtensionMethods.GetName<RuleActionType\>\(RuleActionType\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`BlockMessage = 1` 

Blocks a member's message and prevents it from being posted. 
A custom message can be specified and shown to members whenever their message is blocked.

`SendAlertMessage = 2` 

Logs the user content to a specified channel.

`Timeout = 3` 

Timeout user for a specified duration.

