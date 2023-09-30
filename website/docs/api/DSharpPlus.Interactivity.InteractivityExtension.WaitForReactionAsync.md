# Method WaitForReactionAsync

Namespace: [DSharpPlus.Interactivity](DSharpPlus.Interactivity.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_System_Func_DSharpPlus_EventArgs_MessageReactionAddEventArgs_System_Boolean__System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(Func<MessageReactionAddEventArgs, bool\>, TimeSpan?\)

Wait for a specific reaction.

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(Func<MessageReactionAddEventArgs, bool> predicate, TimeSpan? timeoutoverride = null)
```

### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Predicate to match.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(DiscordMessage, DiscordUser, TimeSpan?\)

Wait for a specific reaction.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(DiscordMessage message, DiscordUser user, TimeSpan? timeoutoverride = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message reaction was added to.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that made the reaction.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_System_Func_DSharpPlus_EventArgs_MessageReactionAddEventArgs_System_Boolean__DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(Func<MessageReactionAddEventArgs, bool\>, DiscordMessage, DiscordUser, TimeSpan?\)

Waits for a specific reaction.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(Func<MessageReactionAddEventArgs, bool> predicate, DiscordMessage message, DiscordUser user, TimeSpan? timeoutoverride = null)
```

### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Predicate to match.

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message reaction was added to.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that made the reaction.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

## <a id="DSharpPlus_Interactivity_InteractivityExtension_WaitForReactionAsync_System_Func_DSharpPlus_EventArgs_MessageReactionAddEventArgs_System_Boolean__DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>WaitForReactionAsync\(Func<MessageReactionAddEventArgs, bool\>, DiscordUser, TimeSpan?\)

Waits for a specific reaction.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task<InteractivityResult<MessageReactionAddEventArgs>> WaitForReactionAsync(Func<MessageReactionAddEventArgs, bool> predicate, DiscordUser user, TimeSpan? timeoutoverride = null)
```

### Parameters

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

predicate to match.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User that made the reaction.

`timeoutoverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Override timeout period.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>\>

