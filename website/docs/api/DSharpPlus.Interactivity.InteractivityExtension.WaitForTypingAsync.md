# Method WaitForTypingAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForTypingAsync_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_TimeSpan__"></a>WaitForTypingAsync\(DiscordChannel, TimeSpan?\)

Waits for any user to start typing.

```csharp
public Task<InteractivityResult<TypingStartEventArgs>> WaitForTypingAsync(DiscordChannel channel, TimeSpan? timeoutoverride = null)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to type in.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>\>

