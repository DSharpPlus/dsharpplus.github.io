# Namespace DSharpPlus.CommandsNext

### Namespaces

[DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)

[DSharpPlus.CommandsNext.Builders](DSharpPlus.CommandsNext.Builders.md)

[DSharpPlus.CommandsNext.Converters](DSharpPlus.CommandsNext.Converters.md)

[DSharpPlus.CommandsNext.Entities](DSharpPlus.CommandsNext.Entities.md)

[DSharpPlus.CommandsNext.Exceptions](DSharpPlus.CommandsNext.Exceptions.md)

[DSharpPlus.CommandsNext.Executors](DSharpPlus.CommandsNext.Executors.md)

### Classes

[BaseCommandModule](DSharpPlus.CommandsNext.BaseCommandModule.md)

Represents a base class for all command modules.

[Command](DSharpPlus.CommandsNext.Command.md)

Represents a command.

[CommandArgument](DSharpPlus.CommandsNext.CommandArgument.md)

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Represents a context in which a command is executed.

[CommandErrorEventArgs](DSharpPlus.CommandsNext.CommandErrorEventArgs.md)

Represents arguments for <xref href="DSharpPlus.CommandsNext.CommandsNextExtension.CommandErrored" data-throw-if-not-resolved="false"></xref> event.

[CommandEventArgs](DSharpPlus.CommandsNext.CommandEventArgs.md)

Base class for all CNext-related events.

[CommandExecutionEventArgs](DSharpPlus.CommandsNext.CommandExecutionEventArgs.md)

Represents arguments for <xref href="DSharpPlus.CommandsNext.CommandsNextExtension.CommandExecuted" data-throw-if-not-resolved="false"></xref> event.

[CommandGroup](DSharpPlus.CommandsNext.CommandGroup.md)

Represents a command group.

[CommandOverload](DSharpPlus.CommandsNext.CommandOverload.md)

Represents a specific overload of a command.

[CommandsNextConfiguration](DSharpPlus.CommandsNext.CommandsNextConfiguration.md)

Represents a configuration for <xref href="DSharpPlus.CommandsNext.CommandsNextExtension" data-throw-if-not-resolved="false"></xref>.

[CommandsNextEvents](DSharpPlus.CommandsNext.CommandsNextEvents.md)

Contains well-defined event IDs used by CommandsNext.

[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)

This is the class which handles command registration, management, and execution.

[CommandsNextUtilities](DSharpPlus.CommandsNext.CommandsNextUtilities.md)

Various CommandsNext-related utilities.

[CommandsNextExtension.DefaultHelpModule](DSharpPlus.CommandsNext.CommandsNextExtension.DefaultHelpModule.md)

[ExtensionMethods](DSharpPlus.CommandsNext.ExtensionMethods.md)

Defines various extensions specific to CommandsNext.

### Structs

[CommandResult](DSharpPlus.CommandsNext.CommandResult.md)

Represents a command's execution result.

### Delegates

[PrefixResolverDelegate](DSharpPlus.CommandsNext.PrefixResolverDelegate.md)

<p>Represents a delegate for a function that takes a message, and returns the position of the start of command invocation in the message. It has to return -1 if prefix is not present.</p>
<p>
It is recommended that helper methods <xref href="DSharpPlus.CommandsNext.CommandsNextUtilities.GetStringPrefixLength(DSharpPlus.Entities.DiscordMessage%2cSystem.String%2cSystem.StringComparison)" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.CommandsNext.CommandsNextUtilities.GetMentionPrefixLength(DSharpPlus.Entities.DiscordMessage%2cDSharpPlus.Entities.DiscordUser)" data-throw-if-not-resolved="false"></xref>
be used internally for checking. Their output can be passed through.
</p>

