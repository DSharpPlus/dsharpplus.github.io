# Class AutoModerationRuleCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents argument for <xref href="DSharpPlus.DiscordClient.AutoModerationRuleCreated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class AutoModerationRuleCreateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[AutoModerationRuleCreateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleCreateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_AutoModerationRuleCreateEventArgs_Rule"></a>Rule

Gets the created rule.

```csharp
public DiscordAutoModerationRule? Rule { get; }
```

#### Property Value

[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)?

