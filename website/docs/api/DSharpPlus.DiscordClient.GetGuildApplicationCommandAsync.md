# Method GetGuildApplicationCommandAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetGuildApplicationCommandAsync_System_UInt64_System_UInt64_"></a>GetGuildApplicationCommandAsync\(ulong, ulong\)

Gets a application command in a guild by its ID.

```csharp
public Task<DiscordApplicationCommand> GetGuildApplicationCommandAsync(ulong guildId, ulong commandId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the application command is in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

