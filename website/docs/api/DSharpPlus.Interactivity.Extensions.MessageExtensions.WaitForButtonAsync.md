# Method WaitForButtonAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_"></a>WaitForButtonAsync\(DiscordMessage\)

Waits for any button to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, TimeSpan?\)

Waits for any button to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, CancellationToken\)

Waits for any button to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, string, TimeSpan?\)

Waits for a button with the specified Id to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, string id, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, string, CancellationToken\)

Waits for a button with the specified Id to be pressed on the specified message.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, string id, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the button to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Waits for any button to be pressed on the specified message by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, DiscordUser user, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for button input from.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, DiscordUser, CancellationToken\)

Waits for any button to be pressed on the specified message by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, DiscordUser user, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for button input from.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)

Waits for any button to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, TimeSpan? timeoutOverride = null)
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

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForButtonAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Threading_CancellationToken_"></a>WaitForButtonAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)

Waits for any button to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForButtonAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, CancellationToken token)
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

