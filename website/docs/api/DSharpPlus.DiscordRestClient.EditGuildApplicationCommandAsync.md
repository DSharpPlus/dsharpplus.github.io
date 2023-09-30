# Method EditGuildApplicationCommandAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_EditGuildApplicationCommandAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_ApplicationCommandEditModel__"></a>EditGuildApplicationCommandAsync\(ulong, ulong, Action<ApplicationCommandEditModel\>\)

Edits a application command in a guild.

```csharp
public Task<DiscordApplicationCommand> EditGuildApplicationCommandAsync(ulong guildId, ulong commandId, Action<ApplicationCommandEditModel> action)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the application command is in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)\>

Action to perform.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The edited command.

