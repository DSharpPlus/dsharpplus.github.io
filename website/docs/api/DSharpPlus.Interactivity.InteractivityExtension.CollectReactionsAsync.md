# Method CollectReactionsAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_CollectReactionsAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>CollectReactionsAsync\(DiscordMessage, TimeSpan?\)

Collects reactions on a specific message.

```csharp
public Task<ReadOnlyCollection<Reaction>> CollectReactionsAsync(DiscordMessage m, TimeSpan? timeoutoverride = null)
```

### Parameters

`m` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to collect reactions on.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[Reaction](DSharpPlus.Interactivity.EventHandling.Reaction.md)\>\>

