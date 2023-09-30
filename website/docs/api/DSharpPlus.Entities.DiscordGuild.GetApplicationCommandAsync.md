# Method GetApplicationCommandAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandAsync_System_UInt64_"></a>GetApplicationCommandAsync\(ulong\)

Gets a application command in this guild by its id.

```csharp
public Task<DiscordApplicationCommand> GetApplicationCommandAsync(ulong commandId)
```

### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

## <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandAsync_System_String_"></a>GetApplicationCommandAsync\(string\)

Gets a application command in this guild by its name.

```csharp
public Task<DiscordApplicationCommand> GetApplicationCommandAsync(string commandName)
```

### Parameters

`commandName` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the command to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the name.

