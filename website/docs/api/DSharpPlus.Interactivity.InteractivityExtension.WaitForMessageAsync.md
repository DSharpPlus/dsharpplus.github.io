# Method WaitForMessageAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForMessageAsync_System_Func_DSharpPlus_Entities_DiscordMessage_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForMessageAsync\(Func<DiscordMessage, bool\>, TimeSpan?\)

Waits for a specific message.

```csharp
public Task<InteractivityResult<DiscordMessage>> WaitForMessageAsync(Func<DiscordMessage, bool> predicate, TimeSpan? timeoutoverride = null)
```

### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Predicate to match.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

