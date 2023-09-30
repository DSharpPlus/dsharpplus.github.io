# Method EditApplicationCommandPermissionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_EditApplicationCommandPermissionsAsync_System_UInt64_System_UInt64_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandPermission__"></a>EditApplicationCommandPermissionsAsync\(ulong, ulong, IEnumerable<DiscordApplicationCommandPermission\>\)

Edits permissions for a application command in a guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> EditApplicationCommandPermissionsAsync(ulong guildId, ulong commandId, IEnumerable<DiscordApplicationCommandPermission> permissions)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit permissions for.

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandPermission](DSharpPlus.Entities.DiscordApplicationCommandPermission.md)\>

The list of permissions to use.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The edited permissions.

