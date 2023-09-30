# Class MessageExtensions

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

Interactivity extension methods for <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>.

```csharp
public static class MessageExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[MessageExtensions](DSharpPlus.Interactivity.Extensions.MessageExtensions.md)

## Methods

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_CollectReactionsAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>CollectReactionsAsync\(DiscordMessage, TimeSpan?\)

Collects all reactions on this message within the timeout duration.

```csharp
public static Task<ReadOnlyCollection<Reaction>> CollectReactionsAsync(this DiscordMessage message, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to collect reactions from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[Reaction](DSharpPlus.Interactivity.EventHandling.Reaction.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_DoPollAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmoji__System_Nullable_DSharpPlus_Interactivity_Enums_PollBehaviour__System_Nullable_System_TimeSpan__"></a>DoPollAsync\(DiscordMessage, IEnumerable<DiscordEmoji\>, PollBehaviour?, TimeSpan?\)

Begins a poll using this message.

```csharp
public static Task<ReadOnlyCollection<PollEmoji>> DoPollAsync(this DiscordMessage message, IEnumerable<DiscordEmoji> emojis, PollBehaviour? behaviorOverride = null, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Target message.

`emojis` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

Options for this poll.

`behaviorOverride` [PollBehaviour](DSharpPlus.Interactivity.Enums.PollBehaviour.md)?

Overrides the action set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.PaginationBehaviour" data-throw-if-not-resolved="false"></xref>

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[PollEmoji](DSharpPlus.Interactivity.EventHandling.PollEmoji.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordMessage, TimeSpan?\)

Waits for the next message that has the same author and channel as this message.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordMessage message, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Original message.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_Entities_DiscordMessage_System_Boolean__System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordMessage, Func<DiscordMessage, bool\>, TimeSpan?\)

Waits for the next message with the same author and channel as this message, which also satisfies a predicate.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordMessage message, Func<DiscordMessage, bool> predicate, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Original message.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A predicate that should return <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if a message matches.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_"></a>WaitForButtonAsync\(DiscordMessage\)

Waits for any button to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, TimeSpan?\)

Waits for any button to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, CancellationToken\)

Waits for any button to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, string, TimeSpan?\)

Waits for a button with the specified Id to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, string id, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, string, CancellationToken\)

Waits for a button with the specified Id to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, string id, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Waits for any button to be pressed on the specified message by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, DiscordUser user, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for button input from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, CancellationToken\)

Waits for any button to be pressed on the specified message by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, DiscordUser user, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for button input from.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)

Waits for any button to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

The predicate to filter interactions by.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)

Waits for any button to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

The predicate to filter interactions by.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A token to cancel interactivity with at any time. Pass <xref href="System.Threading.CancellationToken.None" data-throw-if-not-resolved="false"></xref> to wait indefinitely.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForReactionAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Waits for a reaction on this message from a specific user.

```csharp
public static Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(this DiscordMessage message, DiscordUser user, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Target message.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForReactionAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordEmoji_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(DiscordMessage, DiscordUser, DiscordEmoji, TimeSpan?\)

Waits for a specific reaction on this message from the specified user.

```csharp
public static Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(this DiscordMessage message, DiscordUser user, DiscordEmoji emoji, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Target message.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The target emoji.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)

Waits for any dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A filter predicate.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message doesn't contain any dropdowns

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)

Waits for any dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A filter predicate.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A token that can be used to cancel interactivity. Pass <xref href="System.Threading.CancellationToken.None" data-throw-if-not-resolved="false"></xref> to wait indefinitely.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message doesn't contain any dropdowns

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, string, TimeSpan?\)

Waits for a dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, string id, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, string, CancellationToken\)

Waits for a dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, string id, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_String_System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, DiscordUser, string, TimeSpan?\)

Waits for a dropdown to be interacted with by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, DiscordUser user, string id, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_String_System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, DiscordUser, string, CancellationToken\)

Waits for a dropdown to be interacted with by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, DiscordUser user, string id, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

