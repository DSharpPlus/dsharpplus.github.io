# Method WaitForReactionAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForReactionAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Waits for a reaction on this message from a specific user.

```csharp
public static Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(this DiscordMessage message, DiscordUser user, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Target message.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_WaitForReactionAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordEmoji_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(DiscordMessage, DiscordUser, DiscordEmoji, TimeSpan?\)

Waits for a specific reaction on this message from the specified user.

```csharp
public static Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(this DiscordMessage message, DiscordUser user, DiscordEmoji emoji, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Target message.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The target emoji.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the message.

