# Method CreateGuildApplicationCommandAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_CreateGuildApplicationCommandAsync_System_UInt64_DSharpPlus_Entities_DiscordApplicationCommand_"></a>CreateGuildApplicationCommandAsync\(ulong, DiscordApplicationCommand\)

Creates or overwrites a guild application command.

```csharp
public Task<DiscordApplicationCommand> CreateGuildApplicationCommandAsync(ulong guildId, DiscordApplicationCommand command)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to create the application command in.

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to create.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The created command.

