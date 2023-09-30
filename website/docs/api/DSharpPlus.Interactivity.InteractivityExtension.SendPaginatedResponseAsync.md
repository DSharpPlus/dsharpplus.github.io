# Method SendPaginatedResponseAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_SendPaginatedResponseAsync_DSharpPlus_Entities_DiscordInteraction_System_Boolean_DSharpPlus_Entities_DiscordUser_System_Collections_Generic_IEnumerable_DSharpPlus_Interactivity_Page__DSharpPlus_Interactivity_EventHandling_PaginationButtons_System_Nullable_DSharpPlus_Interactivity_Enums_PaginationBehaviour__System_Nullable_DSharpPlus_Interactivity_Enums_ButtonPaginationBehavior__System_Threading_CancellationToken_System_Boolean_DSharpPlus_Interactivity_Enums_ButtonDisableBehavior_System_Collections_Generic_List_DSharpPlus_Interactivity_Enums_PaginationButtonType__"></a>SendPaginatedResponseAsync\(DiscordInteraction, bool, DiscordUser, IEnumerable<Page\>, PaginationButtons, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken, bool, ButtonDisableBehavior, List<PaginationButtonType\>\)

Sends a paginated message in response to an interaction.
<p>
<b>Pass the interaction directly. Interactivity will ACK it.</b>
</p>

```csharp
public Task SendPaginatedResponseAsync(DiscordInteraction interaction, bool ephemeral, DiscordUser user, IEnumerable<Page> pages, PaginationButtons buttons = null, PaginationBehaviour? behaviour = null, ButtonPaginationBehavior? deletion = null, CancellationToken token = default, bool asEditResponse = false, ButtonDisableBehavior disableBehavior = ButtonDisableBehavior.Disable, List<PaginationButtonType> disabledButtons = null)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

