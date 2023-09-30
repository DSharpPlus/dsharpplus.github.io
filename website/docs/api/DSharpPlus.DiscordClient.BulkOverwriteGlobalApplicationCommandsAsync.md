# Method BulkOverwriteGlobalApplicationCommandsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_BulkOverwriteGlobalApplicationCommandsAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommand__"></a>BulkOverwriteGlobalApplicationCommandsAsync\(IEnumerable<DiscordApplicationCommand\>\)

Overwrites the existing global application commands. New commands are automatically created and missing commands are automatically deleted.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> BulkOverwriteGlobalApplicationCommandsAsync(IEnumerable<DiscordApplicationCommand> commands)
```

### Parameters

`commands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The list of commands to overwrite with.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

The list of global commands.

