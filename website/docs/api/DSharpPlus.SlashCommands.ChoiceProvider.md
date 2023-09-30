# Class ChoiceProvider

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Implementation of <xref href="DSharpPlus.SlashCommands.IChoiceProvider" data-throw-if-not-resolved="false"></xref> with access to service collection.

```csharp
public abstract class ChoiceProvider : IChoiceProvider
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ChoiceProvider](DSharpPlus.SlashCommands.ChoiceProvider.md)

###### Implements

[IChoiceProvider](DSharpPlus.SlashCommands.IChoiceProvider.md)

## Properties

### <a id="DSharpPlus_SlashCommands_ChoiceProvider_GuildId"></a>GuildId

The optional ID of the Guild the command got registered for.

```csharp
public ulong? GuildId { get; set; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_SlashCommands_ChoiceProvider_Services"></a>Services

Sets the service provider.

```csharp
public IServiceProvider Services { get; set; }
```

#### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

## Methods

### <a id="DSharpPlus_SlashCommands_ChoiceProvider_Provider"></a>Provider\(\)

Sets the choices for the slash command.

```csharp
public abstract Task<IEnumerable<DiscordApplicationCommandOptionChoice>> Provider()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandOptionChoice](DSharpPlus.Entities.DiscordApplicationCommandOptionChoice.md)\>\>

