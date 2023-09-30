# Method GetInviteByCodeAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetInviteByCodeAsync_System_String_System_Nullable_System_Boolean__System_Nullable_System_Boolean__"></a>GetInviteByCodeAsync\(string, bool?, bool?\)

Gets an invite.

```csharp
public Task<DiscordInvite> GetInviteByCodeAsync(string code, bool? withCounts = null, bool? withExpiration = null)
```

### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The invite code.

`withCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include presence and total member counts in the returned invite.

`withExpiration` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include the expiration date in the returned invite.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

The requested Invite.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the invite does not exists.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

