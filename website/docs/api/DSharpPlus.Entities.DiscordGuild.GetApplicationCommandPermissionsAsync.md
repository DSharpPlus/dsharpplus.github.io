# Method GetApplicationCommandPermissionsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandPermissionsAsync_DSharpPlus_Entities_DiscordApplicationCommand_"></a>GetApplicationCommandPermissionsAsync\(DiscordApplicationCommand\)

Gets permissions for a application command in this guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> GetApplicationCommandPermissionsAsync(DiscordApplicationCommand command)
```

### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to get them for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The permissions.

