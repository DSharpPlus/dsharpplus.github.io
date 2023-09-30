# Class AutoModerationRuleDeleteEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.AutoModerationRuleDeleted" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class AutoModerationRuleDeleteEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[AutoModerationRuleDeleteEventArgs](DSharpPlus.EventArgs.AutoModerationRuleDeleteEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_AutoModerationRuleDeleteEventArgs_Rule"></a>Rule

Gets the deleted rule.

```csharp
public DiscordAutoModerationRule Rule { get; }
```

#### Property Value

[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)

