# Method RevokeRoleAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMember_RevokeRoleAsync_DSharpPlus_Entities_DiscordRole_System_String_"></a>RevokeRoleAsync\(DiscordRole, string\)

Revokes a role from a member.

```csharp
public Task RevokeRoleAsync(DiscordRole role, string reason = null)
```

### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Role to revoke.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.
