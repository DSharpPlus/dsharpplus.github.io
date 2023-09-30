# Class BaseHelpFormatter

Namespace: [DSharpPlus.CommandsNext.Converters](DSharpPlus.CommandsNext.Converters.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a base class for all default help formatters.

```csharp
public abstract class BaseHelpFormatter
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseHelpFormatter](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md)

###### Derived

[DefaultHelpFormatter](DSharpPlus.CommandsNext.Converters.DefaultHelpFormatter.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Converters_BaseHelpFormatter__ctor_DSharpPlus_CommandsNext_CommandContext_"></a>BaseHelpFormatter\(CommandContext\)

Creates a new help formatter for specified CommandsNext extension instance.

```csharp
public BaseHelpFormatter(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which this formatter is being invoked.

## Properties

### <a id="DSharpPlus_CommandsNext_Converters_BaseHelpFormatter_CommandsNext"></a>CommandsNext

Gets the CommandsNext extension which constructed this help formatter.

```csharp
protected CommandsNextExtension CommandsNext { get; }
```

#### Property Value

[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)

### <a id="DSharpPlus_CommandsNext_Converters_BaseHelpFormatter_Context"></a>Context

Gets the context in which this formatter is being invoked.

```csharp
protected CommandContext Context { get; }
```

#### Property Value

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

## Methods

### <a id="DSharpPlus_CommandsNext_Converters_BaseHelpFormatter_Build"></a>Build\(\)

Constructs the help message.

```csharp
public abstract CommandHelpMessage Build()
```

#### Returns

[CommandHelpMessage](DSharpPlus.CommandsNext.Entities.CommandHelpMessage.md)

Data for the help message.

### <a id="DSharpPlus_CommandsNext_Converters_BaseHelpFormatter_WithCommand_DSharpPlus_CommandsNext_Command_"></a>WithCommand\(Command\)

Sets the command this help message will be for.

```csharp
public abstract BaseHelpFormatter WithCommand(Command command)
```

#### Parameters

`command` [Command](DSharpPlus.CommandsNext.Command.md)

Command for which the help message is being produced.

#### Returns

[BaseHelpFormatter](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md)

This help formatter.

### <a id="DSharpPlus_CommandsNext_Converters_BaseHelpFormatter_WithSubcommands_System_Collections_Generic_IEnumerable_DSharpPlus_CommandsNext_Command__"></a>WithSubcommands\(IEnumerable<Command\>\)

Sets the subcommands for this command, if applicable. This method will be called with filtered data.

```csharp
public abstract BaseHelpFormatter WithSubcommands(IEnumerable<Command> subcommands)
```

#### Parameters

`subcommands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[Command](DSharpPlus.CommandsNext.Command.md)\>

Subcommands for this command group.

#### Returns

[BaseHelpFormatter](DSharpPlus.CommandsNext.Converters.BaseHelpFormatter.md)

This help formatter.

