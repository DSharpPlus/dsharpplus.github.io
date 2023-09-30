# Method WaitForButtonAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordButtonComponent__System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, IEnumerable<DiscordButtonComponent\>, TimeSpan?\)

Waits for any button in the specified collection to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, IEnumerable<DiscordButtonComponent> buttons, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`buttons` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)\>

A collection of buttons to listen for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordButtonComponent__System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, IEnumerable<DiscordButtonComponent\>, CancellationToken\)

Waits for any button in the specified collection to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, IEnumerable<DiscordButtonComponent> buttons, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`buttons` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordButtonComponent](DSharpPlus.Entities.DiscordButtonComponent.md)\>

A collection of buttons to listen for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, TimeSpan?\)

Waits for any button on the specified message to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, CancellationToken\)

Waits for any button on the specified message to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Waits for any button on the specified message to be pressed by the specified user.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, DiscordUser user, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the button press from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, CancellationToken\)

Waits for any button on the specified message to be pressed by the specified user.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, DiscordUser user, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for the button press from.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of button that was pressed, if any.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, string, TimeSpan?\)

Waits for a button with the specified Id to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, string id, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of the operation.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, string, CancellationToken\)

Waits for a button with the specified Id to be pressed.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, string id, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for the button on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

Cancellation token.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

A <xref href="DSharpPlus.Interactivity.InteractivityResult%601" data-throw-if-not-resolved="false"></xref> with the result of the operation.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown when attempting to wait for a message that is not authored by the current user.

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message does not contain a button with the specified Id, or any buttons at all.

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)

Waits for any button to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

The predicate to filter interactions by.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)

Waits for any button to be interacted with.

```csharp
public Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

The predicate to filter interactions by.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A token to cancel interactivity with at any time. Pass <xref href="System.Threading.CancellationToken.None" data-throw-if-not-resolved="false"></xref> to wait indefinitely.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

