# Method DeleteInviteAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteInviteAsync_System_String_System_String_"></a>DeleteInviteAsync\(string, string\)

Removes an invite

```csharp
public Task<DiscordInvite> DeleteInviteAsync(string invite_code, string reason)
```

### Parameters

`invite\_code` [string](https://learn.microsoft.com/dotnet/api/system.string)

Invite code

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this invite was removed

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

