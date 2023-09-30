# Method DoPollAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_DoPollAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmoji__System_Nullable_DSharpPlus_Interactivity_Enums_PollBehaviour__System_Nullable_System_TimeSpan__"></a>DoPollAsync\(DiscordMessage, IEnumerable<DiscordEmoji\>, PollBehaviour?, TimeSpan?\)

Begins a poll using this message.

```csharp
public static Task<ReadOnlyCollection<PollEmoji>> DoPollAsync(this DiscordMessage message, IEnumerable<DiscordEmoji> emojis, PollBehaviour? behaviorOverride = null, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Target message.

`emojis` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

Options for this poll.

`behaviorOverride` [PollBehaviour](DSharpPlus.Interactivity.Enums.PollBehaviour.md)?

Overrides the action set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.PaginationBehaviour" data-throw-if-not-resolved="false"></xref>

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[PollEmoji](DSharpPlus.Interactivity.EventHandling.PollEmoji.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

