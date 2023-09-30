# Method WaitForSelectAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, TimeSpan?\)

Waits for any dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A filter predicate.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override the timeout period specified in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message doesn't contain any dropdowns

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_EventArgs_ComponentInteractionCreateEventArgs_System_Boolean__System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, Func<ComponentInteractionCreateEventArgs, bool\>, CancellationToken\)

Waits for any dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, Func<ComponentInteractionCreateEventArgs, bool> predicate, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait for.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A filter predicate.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A token that can be used to cancel interactivity. Pass <xref href="System.Threading.CancellationToken.None" data-throw-if-not-resolved="false"></xref> to wait indefinitely.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message doesn't contain any dropdowns

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, string, TimeSpan?\)

Waits for a dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, string id, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_System_String_System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, string, CancellationToken\)

Waits for a dropdown to be interacted with.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, string id, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_String_System_Nullable_System_TimeSpan__"></a>WaitForSelectAsync\(DiscordMessage, DiscordUser, string, TimeSpan?\)

Waits for a dropdown to be interacted with by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, DiscordUser user, string id, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForSelectAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_String_System_Threading_CancellationToken_"></a>WaitForSelectAsync\(DiscordMessage, DiscordUser, string, CancellationToken\)

Waits for a dropdown to be interacted with by the specified user.

```csharp
public static Task<InteractivityResult<ComponentInteractionCreateEventArgs>> WaitForSelectAsync(this DiscordMessage message, DiscordUser user, string id, CancellationToken token)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to wait on.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to wait for.

`id` [string](https://learn.microsoft.com/dotnet/api/system.string)

The Id of the dropdown to wait for.

`token` [CancellationToken](https://learn.microsoft.com/dotnet/api/system.threading.cancellationtoken)

A custom cancellation token that can be cancelled at any point.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>\>
