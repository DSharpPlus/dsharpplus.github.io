# Method BatchEditApplicationCommandPermissionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_BatchEditApplicationCommandPermissionsAsync_System_UInt64_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions__"></a>BatchEditApplicationCommandPermissionsAsync\(ulong, IEnumerable<DiscordGuildApplicationCommandPermissions\>\)

Batch edits permissions for a application command in a guild.

```csharp
public Task<IReadOnlyList<DiscordGuildApplicationCommandPermissions>> BatchEditApplicationCommandPermissionsAsync(ulong guildId, IEnumerable<DiscordGuildApplicationCommandPermissions> permissions)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The list of permissions to use.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>\>

A list of edited permissions.

