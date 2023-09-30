# Method DeleteUserReactionAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteUserReactionAsync_System_UInt64_System_UInt64_System_UInt64_System_String_System_String_"></a>DeleteUserReactionAsync\(ulong, ulong, ulong, string, string\)

Deletes someone elses reaction

```csharp
public Task DeleteUserReactionAsync(ulong channel_id, ulong message_id, ulong user_id, string emoji, string reason)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

Emoji to remove

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this reaction was removed

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

