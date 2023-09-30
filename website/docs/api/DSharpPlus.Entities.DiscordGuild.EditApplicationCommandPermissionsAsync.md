# Method EditApplicationCommandPermissionsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_EditApplicationCommandPermissionsAsync_DSharpPlus_Entities_DiscordApplicationCommand_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandPermission__"></a>EditApplicationCommandPermissionsAsync\(DiscordApplicationCommand, IEnumerable<DiscordApplicationCommandPermission\>\)

Edits permissions for a application command in this guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> EditApplicationCommandPermissionsAsync(DiscordApplicationCommand command, IEnumerable<DiscordApplicationCommandPermission> permissions)
```

### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to edit permissions for.

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandPermission](DSharpPlus.Entities.DiscordApplicationCommandPermission.md)\>

The list of permissions to use.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The edited permissions.

