# Method GetInviteAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetInviteAsync_System_String_System_Nullable_System_Boolean__System_Nullable_System_Boolean__"></a>GetInviteAsync\(string, bool?, bool?\)

Gets an invite.

```csharp
public Task<DiscordInvite> GetInviteAsync(string invite_code, bool? withCounts = null, bool? withExpiration = null)
```

### Parameters

`invite\_code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The invite code.

`withCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include presence and total member counts in the returned invite.

`withExpiration` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include the expiration date in the returned invite.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

