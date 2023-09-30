# Method WaitForUserTypingAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_WaitForUserTypingAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForUserTypingAsync\(DiscordChannel, DiscordUser, TimeSpan?\)

Waits for a specific user to start typing in this channel.

```csharp
public static Task<InteractivityResult<TypingStartEventArgs>> WaitForUserTypingAsync(this DiscordChannel channel, DiscordUser user, TimeSpan? timeoutOverride = null)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The target channel.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

