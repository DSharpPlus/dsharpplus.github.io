# Interface IChoiceProvider

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

All choice providers must inherit from this interface.

```csharp
public interface IChoiceProvider
```

## Methods

### <a id="DSharpPlus_SlashCommands_IChoiceProvider_Provider"></a>Provider\(\)

Sets the choices for the slash command.

```csharp
Task<IEnumerable<DiscordApplicationCommandOptionChoice>> Provider()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandOptionChoice](DSharpPlus.Entities.DiscordApplicationCommandOptionChoice.md)\>\>

