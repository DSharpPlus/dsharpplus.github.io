# Method AddOverwriteAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_AddOverwriteAsync_DSharpPlus_Entities_DiscordMember_DSharpPlus_Permissions_DSharpPlus_Permissions_System_String_"></a>AddOverwriteAsync\(DiscordMember, Permissions, Permissions, string\)

Adds a channel permission overwrite for specified member.

```csharp
public Task AddOverwriteAsync(DiscordMember member, Permissions allow = Permissions.None, Permissions deny = Permissions.None, string reason = null)
```

### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to have the permission added.

`allow` [Permissions](DSharpPlus.Permissions.md)

The permissions to allow.

`deny` [Permissions](DSharpPlus.Permissions.md)

The permissions to deny.

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

## <a id="DSharpPlus_Entities_DiscordChannel_AddOverwriteAsync_DSharpPlus_Entities_DiscordRole_DSharpPlus_Permissions_DSharpPlus_Permissions_System_String_"></a>AddOverwriteAsync\(DiscordRole, Permissions, Permissions, string\)

Adds a channel permission overwrite for specified role.

```csharp
public Task AddOverwriteAsync(DiscordRole role, Permissions allow = Permissions.None, Permissions deny = Permissions.None, string reason = null)
```

### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

The role to have the permission added.

`allow` [Permissions](DSharpPlus.Permissions.md)

The permissions to allow.

`deny` [Permissions](DSharpPlus.Permissions.md)

The permissions to deny.

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

