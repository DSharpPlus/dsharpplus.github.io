# Class DefaultHelpFormatter

Namespace: [DSharpPlus.CommandsNext.Converters](DSharpPlus.CommandsNext.Converters.md)  
Assembly: DSharpPlus.CommandsNext.dll

Default CommandsNext help formatter.

```csharp
public class DefaultHelpFormatter : BaseHelpFormatter
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseHelpFormatter](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md) ← 
[DefaultHelpFormatter](DSharpPlus.CommandsNext.Converters.DefaultHelpFormatter.md)

###### Inherited Members

[BaseHelpFormatter.Context](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md\#DSharpPlus\_CommandsNext\_Converters\_BaseHelpFormatter\_Context), 
[BaseHelpFormatter.CommandsNext](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md\#DSharpPlus\_CommandsNext\_Converters\_BaseHelpFormatter\_CommandsNext), 
[BaseHelpFormatter.WithCommand\(Command\)](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md\#DSharpPlus\_CommandsNext\_Converters\_BaseHelpFormatter\_WithCommand\_DSharpPlus\_CommandsNext\_Command\_), 
[BaseHelpFormatter.WithSubcommands\(IEnumerable<Command\>\)](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md\#DSharpPlus\_CommandsNext\_Converters\_BaseHelpFormatter\_WithSubcommands\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_CommandsNext\_Command\_\_), 
[BaseHelpFormatter.Build\(\)](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md\#DSharpPlus\_CommandsNext\_Converters\_BaseHelpFormatter\_Build)

## Constructors

### <a id="DSharpPlus_CommandsNext_Converters_DefaultHelpFormatter__ctor_DSharpPlus_CommandsNext_CommandContext_"></a>DefaultHelpFormatter\(CommandContext\)

Creates a new default help formatter.

```csharp
public DefaultHelpFormatter(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which this formatter is being invoked.

## Properties

### <a id="DSharpPlus_CommandsNext_Converters_DefaultHelpFormatter_EmbedBuilder"></a>EmbedBuilder

```csharp
public DiscordEmbedBuilder EmbedBuilder { get; }
```

#### Property Value

[DiscordEmbedBuilder](DSharpPlus.Entities.DiscordEmbedBuilder.md)

## Methods

### <a id="DSharpPlus_CommandsNext_Converters_DefaultHelpFormatter_Build"></a>Build\(\)

Construct the help message.

```csharp
public override CommandHelpMessage Build()
```

#### Returns

[CommandHelpMessage](DSharpPlus.CommandsNext.Entities.CommandHelpMessage.md)

Data for the help message.

### <a id="DSharpPlus_CommandsNext_Converters_DefaultHelpFormatter_WithCommand_DSharpPlus_CommandsNext_Command_"></a>WithCommand\(Command\)

Sets the command this help message will be for.

```csharp
public override BaseHelpFormatter WithCommand(Command command)
```

#### Parameters

`command` [Command](DSharpPlus.CommandsNext.Command.md)

Command for which the help message is being produced.

#### Returns

[BaseHelpFormatter](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md)

This help formatter.

### <a id="DSharpPlus_CommandsNext_Converters_DefaultHelpFormatter_WithSubcommands_System_Collections_Generic_IEnumerable_DSharpPlus_CommandsNext_Command__"></a>WithSubcommands\(IEnumerable<Command\>\)

Sets the subcommands for this command, if applicable. This method will be called with filtered data.

```csharp
public override BaseHelpFormatter WithSubcommands(IEnumerable<Command> subcommands)
```

#### Parameters

`subcommands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Command](DSharpPlus.CommandsNext.Command.md)\>

Subcommands for this command group.

#### Returns

[BaseHelpFormatter](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md)

This help formatter.

