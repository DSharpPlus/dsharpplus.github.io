# Method TimeoutAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMember_TimeoutAsync_System_Nullable_System_DateTimeOffset__System_String_"></a>TimeoutAsync\(DateTimeOffset?, string\)

Times-out a member and restricts their ability to send messages, add reactions, speak in threads, and join voice channels.

```csharp
public Task TimeoutAsync(DateTimeOffset? until, string reason = null)
```

### Parameters

`until` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

How long the timeout should last. Set to <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> or a time in the past to remove the timeout.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why this member is being restricted.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

