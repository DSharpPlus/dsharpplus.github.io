# Class InteractivityExtension

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

Extension class for DSharpPlus.Interactivity

```csharp
public class InteractivityExtension : BaseExtension
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseExtension](DSharpPlus.BaseExtension.md) ← 
[InteractivityExtension](DSharpPlus.Interactivity.InteractivityExtension.md)

###### Inherited Members

[BaseExtension.Client](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Client), 
[BaseExtension.Dispose\(\)](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Dispose), 
[BaseExtension.Setup\(DiscordClient\)](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Setup\_DSharpPlus\_DiscordClient\_)

## Methods

### <a id="DSharpPlus_Interactivity_InteractivityExtension_CollectEventArgsAsync__1_System_Func___0_System_Boolean__System_Nullable_System_TimeSpan__"></a>CollectEventArgsAsync<T\>\(Func<T, bool\>, TimeSpan?\)

```csharp
public Task<ReadOnlyCollection<T>> CollectEventArgsAsync<T>(Func<T, bool> predicate, TimeSpan? timeoutoverride = null) where T : AsyncEventArgs
```

#### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<T, [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<T\>\>

#### Type Parameters

`T` 

### <a id="DSharpPlus_Interactivity_InteractivityExtension_CollectReactionsAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>CollectReactionsAsync\(DiscordMessage, TimeSpan?\)

Collects reactions on a specific message.

```csharp
public Task<ReadOnlyCollection<Reaction>> CollectReactionsAsync(DiscordMessage m, TimeSpan? timeoutoverride = null)
```

#### Parameters

`m` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to collect reactions on.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[Reaction](DSharpPlus.Interactivity.EventHandling.Reaction.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_Dispose"></a>Dispose\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

```csharp
public override void Dispose()
```

### <a id="DSharpPlus_Interactivity_InteractivityExtension_DoPollAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordEmoji__System_Nullable_DSharpPlus_Interactivity_Enums_PollBehaviour__System_Nullable_System_TimeSpan__"></a>DoPollAsync\(DiscordMessage, IEnumerable<DiscordEmoji\>, PollBehaviour?, TimeSpan?\)

Makes a poll and returns poll results.

```csharp
public Task<ReadOnlyCollection<PollEmoji>> DoPollAsync(DiscordMessage m, IEnumerable<DiscordEmoji> emojis, PollBehaviour? behaviour = null, TimeSpan? timeout = null)
```

#### Parameters

`m` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to create poll on.

`emojis` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

Emojis to use for this poll.

`behaviour` [PollBehaviour](DSharpPlus.Interactivity.Enums.PollBehaviour.md)?

What to do when the poll ends.

`timeout` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.objectmodel.readonlycollection\-1)<[PollEmoji](DSharpPlus.Interactivity.EventHandling.PollEmoji.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_GeneratePagesInContent_System_String_DSharpPlus_Interactivity_Enums_SplitType_"></a>GeneratePagesInContent\(string, SplitType\)

Generates pages from a string, and puts them in message content.

```csharp
public IEnumerable<Page> GeneratePagesInContent(string input, SplitType splittype = SplitType.Character)
```

#### Parameters

`input` [string](https://learn.microsoft.com/dotnet/api/system.string)

Input string.

`splittype` [SplitType](DSharpPlus.Interactivity.Enums.SplitType.md)

How to split input string.

#### Returns

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_GeneratePagesInEmbed_System_String_DSharpPlus_Interactivity_Enums_SplitType_DSharpPlus_Entities_DiscordEmbedBuilder_"></a>GeneratePagesInEmbed\(string, SplitType, DiscordEmbedBuilder\)

Generates pages from a string, and puts them in message embeds.

```csharp
public IEnumerable<Page> GeneratePagesInEmbed(string input, SplitType splittype = SplitType.Character, DiscordEmbedBuilder embedbase = null)
```

#### Parameters

`input` [string](https://learn.microsoft.com/dotnet/api/system.string)

Input string.

`splittype` [SplitType](DSharpPlus.Interactivity.Enums.SplitType.md)

How to split input string.

`embedbase` [DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

Base embed for output embeds.

#### Returns

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to send it on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to give control.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

The pages.

`buttons` [PaginationButtons](DSharpPlus.Interactivity.EventHandling.PaginationButtons.md)

Pagination buttons (pass null to use buttons defined in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>).

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_System_TimeSpan__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons, TimeSpan? timeoutoverride, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to send it on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to give control.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

The pages.

`buttons` [PaginationButtons](DSharpPlus.Interactivity.EventHandling.PaginationButtons.md)

Pagination buttons (pass null to use buttons defined in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>).

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to send it on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to give control.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

The pages.

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Remarks

This is the "default" overload for SendPaginatedMessageAsync, and will use buttons. Feel free to specify default(PaginationEmojis) to use reactions and emojis specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>, instead.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__System_Nullable_System_TimeSpan__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, TimeSpan? timeoutoverride, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to send it on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to give control.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

The pages.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Remarks

This is the "default" overload for SendPaginatedMessageAsync, and will use buttons. Feel free to specify default(PaginationEmojis) to use reactions and emojis specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>, instead.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_PaginationEmojis_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationDeletion__System_Nullable_System_TimeSpan__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationEmojis, PaginationBehaviour?, PaginationDeletion?, TimeSpan?\)

Sends a paginated message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationEmojis emojis, PaginationBehaviour? behaviour = null, PaginationDeletion? deletion = null, TimeSpan? timeoutoverride = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send paginated message in.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to give control.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

Pages.

`emojis` [PaginationEmojis](DSharpPlus.Interactivity.PaginationEmojis.md)

Pagination emojis.

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour (when hitting max and min indices).

`deletion` [PaginationDeletion](DSharpPlus.Interactivity.Enums.PaginationDeletion.md)?

Deletion behaviour.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedResponseAsync_DSharpPlus_Entities_DiscordInteraction_System_Boolean_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_System_Boolean_DSharpPlus_Interactivity_Enums_ButtonDisableBehavior_System_Collections_Generic_List_DSharpPlus_Interactivity_Enums_PaginationButtonType__"></a>SendPaginatedResponseAsync\(DiscordInteraction, bool, DiscordUser, IEnumerable<Page\>, PaginationButtons, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken, bool, ButtonDisableBehavior, List<PaginationButtonType\>\)

Sends a paginated message in response to an interaction.
<p>
<b>Pass the interaction directly. Interactivity will ACK it.</b>
</p>

```csharp
public Task SendPaginatedResponseAsync(DiscordInteraction interaction, bool ephemeral, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons = null, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default, bool asEditResponse = false, ButtonDisableBehavior disableBehavior = ButtonDisableBehavior.Disable, List<PaginationButtonType> disabledButtons = null)
```

#### Parameters

`interaction` [DiscordInteraction](DSharpPlus.Entities.DiscordInteraction.md)

The interaction to create a response to.

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to listen for button presses from.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

The pages to paginate.

`buttons` [PaginationButtons](DSharpPlus.Interactivity.EventHandling.PaginationButtons.md)

Optional: custom buttons

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

`asEditResponse` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

If the response as edit of previous response.

`disableBehavior` [ButtonDisableBehavior](DSharpPlus.Interactivity.Enums.ButtonDisableBehavior.md)

Whether to disable or remove the buttons if there is only one page

`disabledButtons` [List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[PaginationButtonType](DSharpPlus.Interactivity.Enums.PaginationButtonType.md)\>

Disabled buttons

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_InteractivityExtension_Setup_DSharpPlus_DiscordClient_"></a>Setup\(DiscordClient\)

Initializes this extension for given <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> instance.

```csharp
protected override void Setup(DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Discord client to initialize for.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordButtonComponent__System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, IEnumerable<DiscordButtonComponent\>, TimeSpan?\)

Waits for any button in the specified collection to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, IEnumerable<DiscordButtonComponent> buttons, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`buttons` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)\>

A collection of buttons to listen for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordButtonComponent__System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, IEnumerable<DiscordButtonComponent\>, CancellationToken\)

Waits for any button in the specified collection to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, IEnumerable<DiscordButtonComponent> buttons, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`buttons` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)\>

A collection of buttons to listen for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, TimeSpan?\)

Waits for any button on the specified message to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, CancellationToken\)

Waits for any button on the specified message to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Waits for any button on the specified message to be pressed by the specified user.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, DiscordUser user, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the button press from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, CancellationToken\)

Waits for any button on the specified message to be pressed by the specified user.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, DiscordUser user, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the button press from.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, string, TimeSpan?\)

Waits for a button with the specified Id to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, string id, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of the operation.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, string, CancellationToken\)

Waits for a button with the specified Id to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, string id, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

Cancellation token.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of the operation.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)

Waits for any button to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, TimeSpan? timeoutOverride = null)
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

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)

Waits for any button to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, CancellationToken token)
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

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForCustomComponentPaginationAsync_DSharpPlus_Interactivity_EventHandling_IPaginationRequest_"></a>WaitForCustomComponentPaginationAsync\(IPaginationRequest\)

Waits for custom button-based pagination request to finish.
<br />
This does <i><b>not</b></i> invoke <xref href="DSharpPlus.Interactivity.EventHandling.IPaginationRequest.DoCleanupAsync" data-throw-if-not-resolved="false"></xref>.

```csharp
public Task WaitForCustomComponentPaginationAsync(IPaginationRequest request)
```

#### Parameters

`request` [IPaginationRequest](DSharpPlus.Interactivity.EventHandling.IPaginationRequest.md)

The request to wait for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForCustomPaginationAsync_DSharpPlus_Interactivity_EventHandling_IPaginationRequest_"></a>WaitForCustomPaginationAsync\(IPaginationRequest\)

Waits for a custom pagination request to finish.
This does NOT handle removing emojis after finishing for you.

```csharp
public Task WaitForCustomPaginationAsync(IPaginationRequest request)
```

#### Parameters

`request` [IPaginationRequest](DSharpPlus.Interactivity.EventHandling.IPaginationRequest.md)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForEventArgsAsync__1_System_Func___0_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForEventArgsAsync<T\>\(Func<T, bool\>, TimeSpan?\)

Waits for specific event args to be received. Make sure the appropriate <xref href="DSharpPlus.DiscordIntents" data-throw-if-not-resolved="false"></xref> are registered, if needed.

```csharp
public Task<InteractivityResult<T>> WaitForEventArgsAsync<T>(Func<T, bool> predicate, TimeSpan? timeoutoverride = null) where T : AsyncEventArgs
```

#### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<T, [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<T\>\>

#### Type Parameters

`T` 

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForMessageAsync_System_Func_DSharpPlus_Entities_DiscordMessage_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForMessageAsync\(Func<DiscordMessage, bool\>, TimeSpan?\)

Waits for a specific message.

```csharp
public Task<InteractivityResult<DiscordMessage>> WaitForMessageAsync(Func<DiscordMessage, bool> predicate, TimeSpan? timeoutoverride = null)
```

#### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Predicate to match.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_System_Nullable_System_TimeSpan__"></a>WaitForModalAsync\(string, TimeSpan?\)

Waits for a modal with the specified id to be submitted.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, TimeSpan? timeoutOverride = null)
```

#### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_System_Threading_CancellationToken_"></a>WaitForModalAsync\(string, CancellationToken\)

Waits for a modal with the specified id to be submitted.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, CancellationToken token)
```

#### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForModalAsync\(string, DiscordUser, TimeSpan?\)

Waits for a modal with the specificed custom id to be submitted by the given user.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, DiscordUser user, TimeSpan? timeoutOverride = null)
```

#### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the modal from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_DSharpPlus_Entities_DiscordUser_System_Threading_CancellationToken_"></a>WaitForModalAsync\(string, DiscordUser, CancellationToken\)

Waits for a modal with the specificed custom id to be submitted by the given user.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, DiscordUser user, CancellationToken token)
```

#### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the modal from.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_System_Func_DSharpPlus_EventArgs_MessageReactionAddEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(Func<MessageReactionAddEventArgs, bool\>, TimeSpan?\)

Wait for a specific reaction.

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(Func<MessageReactionAddEventArgs, bool> predicate, TimeSpan? timeoutoverride = null)
```

#### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Predicate to match.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Wait for a specific reaction.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(DiscordMessage message, DiscordUser user, TimeSpan? timeoutoverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message reaction was added to.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that made the reaction.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_System_Func_DSharpPlus_EventArgs_MessageReactionAddEventArgs_System_Boolean__DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(Func<MessageReactionAddEventArgs, bool\>, DiscordMessage, DiscordUser, TimeSpan?\)

Waits for a specific reaction.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(Func<MessageReactionAddEventArgs, bool> predicate, DiscordMessage message, DiscordUser user, TimeSpan? timeoutoverride = null)
```

#### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Predicate to match.

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message reaction was added to.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that made the reaction.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_System_Func_DSharpPlus_EventArgs_MessageReactionAddEventArgs_System_Boolean__DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(Func<MessageReactionAddEventArgs, bool\>, DiscordUser, TimeSpan?\)

Waits for a specific reaction.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(Func<MessageReactionAddEventArgs, bool> predicate, DiscordUser user, TimeSpan? timeoutoverride = null)
```

#### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

predicate to match.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that made the reaction.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)

Waits for any dropdown to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, TimeSpan? timeoutOverride = null)
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

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)

Waits for any dropdown to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, CancellationToken token)
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

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, string, TimeSpan?\)

Waits for a dropdown to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(DiscordMessage message, string id, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait on.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

#### Remarks

This is here for backwards-compatibility and will internally create a cancellation token.

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not have any dropdowns or any dropdown with the specified Id.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, string, CancellationToken\)

Waits for a dropdown to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(DiscordMessage message, string id, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait on.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not have any dropdowns or any dropdown with the specified Id.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_String_System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, DiscordUser, string, TimeSpan?\)

Waits for a dropdown to be interacted with by a specific user.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(DiscordMessage message, DiscordUser user, string id, TimeSpan? timeoutOverride = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait on.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not have any dropdowns or any dropdown with the specified Id.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_String_System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, DiscordUser, string, CancellationToken\)

Waits for a dropdown to be interacted with by a specific user.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(DiscordMessage message, DiscordUser user, string id, CancellationToken token)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait on.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not have any dropdowns or any dropdown with the specified Id.

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForTypingAsync_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_TimeSpan__"></a>WaitForTypingAsync\(DiscordChannel, TimeSpan?\)

Waits for any user to start typing.

```csharp
public Task<InteractivityResult<TypingStartEventArgs>> WaitForTypingAsync(DiscordChannel channel, TimeSpan? timeoutoverride = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to type in.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForUserTypingAsync_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_TimeSpan__"></a>WaitForUserTypingAsync\(DiscordUser, DiscordChannel, TimeSpan?\)

Waits for a user to start typing.

```csharp
public Task<InteractivityResult<TypingStartEventArgs>> WaitForUserTypingAsync(DiscordUser user, DiscordChannel channel, TimeSpan? timeoutoverride = null)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that starts typing.

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel the user is typing in.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

### <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForUserTypingAsync_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForUserTypingAsync\(DiscordUser, TimeSpan?\)

Waits for a user to start typing.

```csharp
public Task<InteractivityResult<TypingStartEventArgs>> WaitForUserTypingAsync(DiscordUser user, TimeSpan? timeoutoverride = null)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that starts typing.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

