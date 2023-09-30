# Method UpdateStatusAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_UpdateStatusAsync_DSharpPlus_Entities_DiscordActivity_System_Nullable_DSharpPlus_Entities_UserStatus__System_Nullable_System_DateTimeOffset__"></a>UpdateStatusAsync\(DiscordActivity, UserStatus?, DateTimeOffset?\)

Updates current user's activity and status.

```csharp
public Task UpdateStatusAsync(DiscordActivity activity = null, UserStatus? userStatus = null, DateTimeOffset? idleSince = null)
```

### Parameters

`activity` [DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)

Activity to set.

`userStatus` [UserStatus](DSharpPlus.Entities.UserStatus.md)?

Status of the user.

`idleSince` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Since when is the client performing the specified activity.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

