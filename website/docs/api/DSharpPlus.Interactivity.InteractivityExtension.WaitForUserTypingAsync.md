# Method WaitForUserTypingAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForUserTypingAsync_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_TimeSpan__"></a>WaitForUserTypingAsync\(DiscordUser, DiscordChannel, TimeSpan?\)

Waits for a user to start typing.

```csharp
public Task<InteractivityResult<TypingStartEventArgs>> WaitForUserTypingAsync(DiscordUser user, DiscordChannel channel, TimeSpan? timeoutoverride = null)
```

### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that starts typing.

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel the user is typing in.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForUserTypingAsync_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForUserTypingAsync\(DiscordUser, TimeSpan?\)

Waits for a user to start typing.

```csharp
public Task<InteractivityResult<TypingStartEventArgs>> WaitForUserTypingAsync(DiscordUser user, TimeSpan? timeoutoverride = null)
```

### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that starts typing.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

