# Method GetGuildApplicationCommandsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildApplicationCommandsAsync_System_UInt64_"></a>GetGuildApplicationCommandsAsync\(ulong\)

Gets all the application commands for a guild.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> GetGuildApplicationCommandsAsync(ulong guildId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to get application commands for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

A list of application commands in the guild.

