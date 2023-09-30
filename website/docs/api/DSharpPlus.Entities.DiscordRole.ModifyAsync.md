# Method ModifyAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordRole_ModifyAsync_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Entities_DiscordColor__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>ModifyAsync\(string, Permissions?, DiscordColor?, bool?, bool?, string, Stream, DiscordEmoji\)

Updates this role.

```csharp
public Task ModifyAsync(string name = null, Permissions? permissions = null, DiscordColor? color = null, bool? hoist = null, bool? mentionable = null, string reason = null, Stream icon = null, DiscordEmoji emoji = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New role name

`permissions` [Permissions](DSharpPlus.Permissions.md)?

New role permissions

`color` [DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

New role color

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

New role hoist

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role is mentionable

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why we made this change

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordRole_ModifyAsync_System_Action_DSharpPlus_Net_Models_RoleEditModel__"></a>ModifyAsync\(Action<RoleEditModel\>\)

```csharp
public Task ModifyAsync(Action<RoleEditModel> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[RoleEditModel](DSharpPlus.Net.Models.RoleEditModel.md)\>

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the<xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

