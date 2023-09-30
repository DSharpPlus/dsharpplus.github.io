# Method GetNextMessageAsync

Namespace: [DSharpPlus.Interactivity.Extensions](DSharpPlus.Interactivity.Extensions.md)  
Assembly: DSharpPlus.Interactivity.dll

## <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordChannel_System_Func_DSharpPlus_Entities_DiscordMessage_System_Boolean__System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordChannel, Func<DiscordMessage, bool\>, TimeSpan?\)

Waits for the next message sent in this channel that satisfies the predicate.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordChannel channel, Func<DiscordMessage, bool> predicate, TimeSpan? timeoutOverride = null)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to monitor.

`predicate` [Func](https://learn.microsoft.com/dotnet/api/system.func\-2)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md), [bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

A predicate that should return <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if a message matches.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

## <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordChannel, TimeSpan?\)

Waits for the next message sent in this channel.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordChannel channel, TimeSpan? timeoutOverride = null)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to monitor.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

## <a id="DSharpPlus_Interactivity_Extensions_ChannelExtensions_GetNextMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordUser_System_Nullable_System_TimeSpan__"></a>GetNextMessageAsync\(DiscordChannel, DiscordUser, TimeSpan?\)

Waits for the next message sent in this channel from a specific user.

```csharp
public static Task<InteractivityResult<DiscordMessage>> GetNextMessageAsync(this DiscordChannel channel, DiscordUser user, TimeSpan? timeoutOverride = null)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel to monitor.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The target user.

`timeoutOverride` [TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)?

Overrides the timeout set in <xref href="DSharpPlus.Interactivity.InteractivityConfiguration.Timeout" data-throw-if-not-resolved="false"></xref>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[InteractivityResult](DSharpPlus.Interactivity.InteractivityResult\-1.md)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

Thrown if interactivity is not enabled for the client associated with the channel.

