# Method SendPaginatedMessageAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_System_TimeSpan__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons, TimeSpan? timeoutoverride, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Remarks

This is the "default" overload for SendPaginatedMessageAsync, and will use buttons. Feel free to specify default(PaginationEmojis) to use reactions and emojis specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>, instead.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__System_Nullable_System_TimeSpan__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)

Sends a paginated message with buttons.

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, TimeSpan? timeoutoverride, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Remarks

This is the "default" overload for SendPaginatedMessageAsync, and will use buttons. Feel free to specify default(PaginationEmojis) to use reactions and emojis specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>, instead.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_PaginationEmojis_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_PaginationDeletion__System_Nullable_System_TimeSpan__"></a>SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationEmojis, PaginationBehaviour?, PaginationDeletion?, TimeSpan?\)

Sends a paginated message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task SendPaginatedMessageAsync(DiscordChannel channel, DiscordUser user, IEnumerable<Page> pages, PaginationEmojis emojis, PaginationBehaviour? behaviour = null, PaginationDeletion? deletion = null, TimeSpan? timeoutoverride = null)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

