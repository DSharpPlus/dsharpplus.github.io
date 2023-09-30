# Method DoPollAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_DoPollAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmoji__System_Nullable_DSharpPlus_Interactivity_Enums_PollBehaviour__System_Nullable_System_TimeSpan__"></a>DoPollAsync\(DiscordMessage, IEnumerable<DiscordEmoji\>, PollBehaviour?, TimeSpan?\)

Makes a poll and returns poll results.

```csharp
public Task<ReadOnlyCollection<PollEmoji>> DoPollAsync(DiscordMessage m, IEnumerable<DiscordEmoji> emojis, PollBehaviour? behaviour = null, TimeSpan? timeout = null)
```

### Parameters

`m` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to create poll on.

`emojis` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

Emojis to use for this poll.

`behaviour` [PollBehaviour](DSharpPlus.Interactivity.Enums.PollBehaviour.md)?

What to do when the poll ends.

`timeout` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[PollEmoji](DSharpPlus.Interactivity.EventHandling.PollEmoji.md)\>\>

