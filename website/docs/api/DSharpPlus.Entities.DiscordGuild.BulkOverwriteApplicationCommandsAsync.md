# Method BulkOverwriteApplicationCommandsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_BulkOverwriteApplicationCommandsAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommand__"></a>BulkOverwriteApplicationCommandsAsync\(IEnumerable<DiscordApplicationCommand\>\)

Overwrites the existing application commands in this guild. New commands are automatically created and missing commands are automatically delete

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> BulkOverwriteApplicationCommandsAsync(IEnumerable<DiscordApplicationCommand> commands)
```

### Parameters

`commands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The list of commands to overwrite with.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

The list of guild commands

