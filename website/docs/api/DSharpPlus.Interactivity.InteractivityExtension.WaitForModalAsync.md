# Method WaitForModalAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_System_Nullable_System_TimeSpan__"></a>WaitForModalAsync\(string, TimeSpan?\)

Waits for a modal with the specified id to be submitted.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, TimeSpan? timeoutOverride = null)
```

### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_System_Threading_CancellationToken_"></a>WaitForModalAsync\(string, CancellationToken\)

Waits for a modal with the specified id to be submitted.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, CancellationToken token)
```

### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForModalAsync\(string, DiscordUser, TimeSpan?\)

Waits for a modal with the specificed custom id to be submitted by the given user.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, DiscordUser user, TimeSpan? timeoutOverride = null)
```

### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the modal from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForModalAsync_System_String_DSharpPlus_Entities_DiscordUser_System_Threading_CancellationToken_"></a>WaitForModalAsync\(string, DiscordUser, CancellationToken\)

Waits for a modal with the specificed custom id to be submitted by the given user.

```csharp
public Task<InteractivityResult<ModalSubmitEventArgs>> WaitForModalAsync(string modal_id, DiscordUser user, CancellationToken token)
```

### Parameters

`modal\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The id of the modal to wait for. Should be unique to avoid issues.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the modal from.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with a modal if the interactivity did not time out.

