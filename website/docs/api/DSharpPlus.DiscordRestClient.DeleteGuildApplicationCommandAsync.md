# Method DeleteGuildApplicationCommandAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteGuildApplicationCommandAsync_System_UInt64_System_UInt64_"></a>DeleteGuildApplicationCommandAsync\(ulong, ulong\)

Deletes a application command in a guild.

```csharp
public Task DeleteGuildApplicationCommandAsync(ulong guildId, ulong commandId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to delete the application command in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

