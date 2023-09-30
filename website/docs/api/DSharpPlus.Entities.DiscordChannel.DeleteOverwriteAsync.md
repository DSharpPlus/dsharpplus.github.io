# Method DeleteOverwriteAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_DeleteOverwriteAsync_DSharpPlus_Entities_DiscordMember_System_String_"></a>DeleteOverwriteAsync\(DiscordMember, string\)

Deletes a channel permission overwrite for the specified member.

```csharp
public Task DeleteOverwriteAsync(DiscordMember member, string reason = null)
```

### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to have the permission deleted.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordChannel_DeleteOverwriteAsync_DSharpPlus_Entities_DiscordRole_System_String_"></a>DeleteOverwriteAsync\(DiscordRole, string\)

Deletes a channel permission overwrite for the specified role.

```csharp
public Task DeleteOverwriteAsync(DiscordRole role, string reason = null)
```

### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

The role to have the permission deleted.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

