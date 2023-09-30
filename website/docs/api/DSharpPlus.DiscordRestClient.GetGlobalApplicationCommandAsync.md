# Method GetGlobalApplicationCommandAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGlobalApplicationCommandAsync_System_UInt64_"></a>GetGlobalApplicationCommandAsync\(ulong\)

Gets a global application command by its ID.

```csharp
public Task<DiscordApplicationCommand> GetGlobalApplicationCommandAsync(ulong commandId)
```

### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

