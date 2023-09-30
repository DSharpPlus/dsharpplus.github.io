# Method CollectReactionsAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_CollectReactionsAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>CollectReactionsAsync\(DiscordMessage, TimeSpan?\)

Collects all reactions on this message within the timeout duration.

```csharp
public static Task<ReadOnlyCollection<Reaction>> CollectReactionsAsync(this DiscordMessage message, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to collect reactions from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[Reaction](DSharpPlus.Interactivity.EventHandling.Reaction.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

