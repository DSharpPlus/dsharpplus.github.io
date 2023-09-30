# Method GetGuildApplicationCommandsPermissionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildApplicationCommandsPermissionsAsync_System_UInt64_"></a>GetGuildApplicationCommandsPermissionsAsync\(ulong\)

Gets all application command permissions in a guild.

```csharp
public Task<IReadOnlyList<DiscordGuildApplicationCommandPermissions>> GetGuildApplicationCommandsPermissionsAsync(ulong guildId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>\>

A list of permissions.

