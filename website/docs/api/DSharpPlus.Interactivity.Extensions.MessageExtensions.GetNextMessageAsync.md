# Method GetNextMessageAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordMessage_System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordMessage, TimeSpan?\)

Waits for the next message that has the same author and channel as this message.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordMessage message, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Original message.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

## <a id="DSharpPlus_Interactivity_Extensions_MessageExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordMessage_System_Func_DSharpPlus_Entities_DiscordMessage_System_Boolean__System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordMessage, Func<DiscordMessage, bool\>, TimeSpan?\)

Waits for the next message with the same author and channel as this message, which also satisfies a predicate.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordMessage message, Func<DiscordMessage, bool> predicate, TimeSpan? timeoutOverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Original message.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A predicate that should return <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if a message matches.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

