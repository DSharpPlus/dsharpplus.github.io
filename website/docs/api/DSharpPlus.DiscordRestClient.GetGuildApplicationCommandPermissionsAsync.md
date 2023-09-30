# Method GetGuildApplicationCommandPermissionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildApplicationCommandPermissionsAsync_System_UInt64_System_UInt64_"></a>GetGuildApplicationCommandPermissionsAsync\(ulong, ulong\)

Gets permissions for a application command in a guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> GetGuildApplicationCommandPermissionsAsync(ulong guildId, ulong commandId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get them for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The permissions.

