# Class ChannelExtensions

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

Interactivity extension methods for <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref>.

```csharp
public static class ChannelExtensions
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ChannelExtensions](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md)

## Methods

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordChannel_System_Func_DSharpPlus_Entities_DiscordMessage_System_Boolean__System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordChannel, Func<DiscordMessage, bool\>, TimeSpan?\)

Waits for the next message sent in this channel that satisfies the predicate.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordChannel channel, Func<DiscordMessage, bool> predicate, TimeSpan? timeoutOverride = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to monitor.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A predicate that should return <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if a message matches.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordChannel, TimeSpan?\)

Waits for the next message sent in this channel.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordChannel channel, TimeSpan? timeoutOverride = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to monitor.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordChannel, DiscordUser, TimeSpan?\)

Waits for the next message sent in this channel from a specific user.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordChannel channel, DiscordUser user, TimeSpan? timeoutOverride = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to monitor.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_PaginationEmojis_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationDeletion__System_Nullable_System_TimeSpan__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationEmojis, PaginationBehaviour?, PaginationDeletion?, TimeSpan?\)

Sends a new paginated message.

```csharp
public static Task SendPaginatedMessageAsync(this DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationEmojis emojis, PaginationBehaviour? behaviour = null, PaginationDeletion? deletion = null, TimeSpan? timeoutoverride = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Target channel.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user that'll be able to control the pages.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

A collection of <xref href="DSharpPlus.Interactivity.Page" data-throw-if-not-resolved="false"></xref> to display.

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

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)

Sends a new paginated message with buttons.

```csharp
public static Task SendPaginatedMessageAsync(this DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Target channel.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user that'll be able to control the pages.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

A collection of <xref href="DSharpPlus.Interactivity.Page" data-throw-if-not-resolved="false"></xref> to display.

`buttons` [PaginationButtons](DSharpPlus.Interactivity.EventHandling.PaginationButtons.md)

Pagination buttons (leave null to default to ones on configuration).

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)

Sends a new paginated message with buttons.

```csharp
public static Task SendPaginatedMessageAsync(this DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Target channel.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user that'll be able to control the pages.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

A collection of <xref href="DSharpPlus.Interactivity.Page" data-throw-if-not-resolved="false"></xref> to display.

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_System_TimeSpan__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)

Sends a new paginated message with buttons.

```csharp
public static Task SendPaginatedMessageAsync(this DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons, TimeSpan? timeoutoverride, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Target channel.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user that'll be able to control the pages.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

A collection of <xref href="DSharpPlus.Interactivity.Page" data-throw-if-not-resolved="false"></xref> to display.

`buttons` [PaginationButtons](DSharpPlus.Interactivity.EventHandling.PaginationButtons.md)

Pagination buttons (leave null to default to ones on configuration).

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__System_Nullable_System_TimeSpan__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)

Sends a new paginated message with buttons.

```csharp
public static Task SendPaginatedMessageAsync(this DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, TimeSpan? timeoutoverride, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Target channel.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user that'll be able to control the pages.

`pages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Page](DSharpPlus.Interactivity.Page.md)\>

A collection of <xref href="DSharpPlus.Interactivity.Page" data-throw-if-not-resolved="false"></xref> to display.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

`behaviour` [PaginationBehaviour](DSharpPlus.Interactivity.Enums.PaginationBehaviour.md)?

Pagination behaviour.

`deletion` [ButtonPaginationBehavior](DSharpPlus.Interactivity.Enums.ButtonPaginationBehavior.md)?

Deletion behaviour

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

### <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_WaitForUserTypingAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForUserTypingAsync\(DiscordChannel, DiscordUser, TimeSpan?\)

Waits for a specific user to start typing in this channel.

```csharp
public static Task<InteractivityResult<TypingStartEventArgs>> WaitForUserTypingAsync(this DiscordChannel channel, DiscordUser user, TimeSpan? timeoutOverride = null)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The target channel.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

