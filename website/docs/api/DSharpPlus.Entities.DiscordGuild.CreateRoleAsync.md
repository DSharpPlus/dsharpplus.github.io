# Method CreateRoleAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateRoleAsync_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Entities_DiscordColor__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>CreateRoleAsync\(string, Permissions?, DiscordColor?, bool?, bool?, string, Stream, DiscordEmoji\)

Creates a new role in this guild.

```csharp
public Task<DiscordRole> CreateRoleAsync(string name = null, Permissions? permissions = null, DiscordColor? color = null, bool? hoist = null, bool? mentionable = null, string reason = null, Stream icon = null, DiscordEmoji emoji = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the role.

`permissions` [Permissions](DSharpPlus.Permissions.md)?

Permissions for the role.

`color` [DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

Color for the role.

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the role is to be hoisted.

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the role is to be mentionable.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The newly-created role.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

