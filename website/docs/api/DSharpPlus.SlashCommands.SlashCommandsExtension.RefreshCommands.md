# Method RefreshCommands

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RefreshCommands"></a>RefreshCommands\(\)

<p>Refreshes your commands, used for refreshing choice providers or applying commands registered after the ready event on the discord client.
Should only be run on the slash command extension linked to shard 0 if sharding.</p>
<p>Not recommended and should be avoided since it can make slash commands be unresponsive for a while.</p>

```csharp
public Task RefreshCommands()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

