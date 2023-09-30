# Method EditGlobalApplicationCommandAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_EditGlobalApplicationCommandAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_ApplicationCommandEditModel__"></a>EditGlobalApplicationCommandAsync\(ulong, Action<ApplicationCommandEditModel\>\)

Edits a global application command.

```csharp
public Task<DiscordApplicationCommand> EditGlobalApplicationCommandAsync(ulong commandId, Action<ApplicationCommandEditModel> action)
```

### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)\>

Action to perform.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The edited command.

