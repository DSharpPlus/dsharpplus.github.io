# Method ModifyGuildRoleAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildRoleAsync_System_UInt64_System_UInt64_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Entities_DiscordColor__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>ModifyGuildRoleAsync\(ulong, ulong, string, Permissions?, DiscordColor?, bool?, bool?, string, Stream, DiscordEmoji\)

Modifies a role

```csharp
public Task<DiscordRole> ModifyGuildRoleAsync(ulong guild_id, ulong role_id, string name, Permissions? permissions, DiscordColor? color, bool? hoist, bool? mentionable, string reason, Stream icon, DiscordEmoji emoji)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New role name

`permissions` [Permissions](DSharpPlus.Permissions.md)?

New role permissions

`color` [DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

New role color

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be hoisted

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be mentionable

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why this role was modified

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildRoleAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_RoleEditModel__"></a>ModifyGuildRoleAsync\(ulong, ulong, Action<RoleEditModel\>\)

Modifies a role

```csharp
public Task ModifyGuildRoleAsync(ulong role_id, ulong guild_id, Action<RoleEditModel> action)
```

### Parameters

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[RoleEditModel](DSharpPlus.Net.Models.RoleEditModel.md)\>

Modifications

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

