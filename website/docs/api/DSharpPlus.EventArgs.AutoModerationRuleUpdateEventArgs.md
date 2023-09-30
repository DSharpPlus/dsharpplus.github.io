# Class AutoModerationRuleUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.AutoModerationRuleUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class AutoModerationRuleUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[AutoModerationRuleUpdateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_AutoModerationRuleUpdateEventArgs_Rule"></a>Rule

Gets the updated rule.

```csharp
public DiscordAutoModerationRule? Rule { get; }
```

#### Property Value

[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)?

