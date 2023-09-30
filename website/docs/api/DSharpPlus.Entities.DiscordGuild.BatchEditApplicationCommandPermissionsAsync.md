# Method BatchEditApplicationCommandPermissionsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_BatchEditApplicationCommandPermissionsAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions__"></a>BatchEditApplicationCommandPermissionsAsync\(IEnumerable<DiscordGuildApplicationCommandPermissions\>\)

Batch edits permissions for a application command in this guild.

```csharp
public Task<IReadOnlyList<DiscordGuildApplicationCommandPermissions>> BatchEditApplicationCommandPermissionsAsync(IEnumerable<DiscordGuildApplicationCommandPermissions> permissions)
```

### Parameters

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The list of permissions to use.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>\>

A list of edited permissions.

