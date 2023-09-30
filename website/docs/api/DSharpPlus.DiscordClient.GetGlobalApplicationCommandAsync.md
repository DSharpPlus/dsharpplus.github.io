# Method GetGlobalApplicationCommandAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetGlobalApplicationCommandAsync_System_UInt64_"></a>GetGlobalApplicationCommandAsync\(ulong\)

Gets a global application command by its id.

```csharp
public Task<DiscordApplicationCommand> GetGlobalApplicationCommandAsync(ulong commandId)
```

### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

## <a id="DSharpPlus_DiscordClient_GetGlobalApplicationCommandAsync_System_String_"></a>GetGlobalApplicationCommandAsync\(string\)

Gets a global application command by its name.

```csharp
public Task<DiscordApplicationCommand> GetGlobalApplicationCommandAsync(string commandName)
```

### Parameters

`commandName` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the command to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the name.

