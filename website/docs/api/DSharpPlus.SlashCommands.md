# Namespace DSharpPlus.SlashCommands

### Namespaces

[DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)

[DSharpPlus.SlashCommands.EventArgs](DSharpPlus.SlashCommands.EventArgs.md)

### Classes

[ApplicationCommandModule](DSharpPlus.SlashCommands.ApplicationCommandModule.md)

Represents a base class for slash command modules.

[AutocompleteAttribute](DSharpPlus.SlashCommands.AutocompleteAttribute.md)

Handles autocomplete choices for a slash command parameter.

[AutocompleteContext](DSharpPlus.SlashCommands.AutocompleteContext.md)

Represents a context for an autocomplete interaction.

[BaseContext](DSharpPlus.SlashCommands.BaseContext.md)

Represents a base context for application command contexts.

[ChannelTypesAttribute](DSharpPlus.SlashCommands.ChannelTypesAttribute.md)

Defines allowed channel types for a channel parameter.

[ChoiceAttribute](DSharpPlus.SlashCommands.ChoiceAttribute.md)

Adds a choice for this slash command option.

[ChoiceNameAttribute](DSharpPlus.SlashCommands.ChoiceNameAttribute.md)

Sets the name for this enum choice.

[ChoiceProvider](DSharpPlus.SlashCommands.ChoiceProvider.md)

Implementation of <xref href="DSharpPlus.SlashCommands.IChoiceProvider" data-throw-if-not-resolved="false"></xref> with access to service collection.

[ChoiceProviderAttribute](DSharpPlus.SlashCommands.ChoiceProviderAttribute.md)

Sets a IChoiceProvider for a command options. ChoiceProviders can be used to provide
DiscordApplicationCommandOptionChoice from external sources such as a database.

[ContextMenuAttribute](DSharpPlus.SlashCommands.ContextMenuAttribute.md)

Marks this method as a context menu.

[ContextMenuCheckBaseAttribute](DSharpPlus.SlashCommands.ContextMenuCheckBaseAttribute.md)

The base class for a pre-execution check for a context menu.

[ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md)

Represents a context for a context menu.

[ContextMenuExecutionChecksFailedException](DSharpPlus.SlashCommands.ContextMenuExecutionChecksFailedException.md)

Thrown when a pre-execution check for a slash command fails.

[DescriptionLocalizationAttribute](DSharpPlus.SlashCommands.DescriptionLocalizationAttribute.md)

Specifies a locale for a slash command description. The longest description is the one that counts toward character limits.

[DontInjectAttribute](DSharpPlus.SlashCommands.DontInjectAttribute.md)

Prevents this field or property from having its value injected by dependency injection.

[ExtensionMethods](DSharpPlus.SlashCommands.ExtensionMethods.md)

Defines various extension methods for slash commands.

[GuildOnlyAttribute](DSharpPlus.SlashCommands.GuildOnlyAttribute.md)

Indicates that a global application command cannot be invoked in DMs.

[InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

Represents a context for an interaction.

[LocaleHelper](DSharpPlus.SlashCommands.LocaleHelper.md)

A helper class that provides a list of supported localizations.

[MaximumAttribute](DSharpPlus.SlashCommands.MaximumAttribute.md)

Sets a maximum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

[MaximumLengthAttribute](DSharpPlus.SlashCommands.MaximumLengthAttribute.md)

Sets a maximum allowed length for this slash command option. Only valid for <xref href="System.String" data-throw-if-not-resolved="false"></xref> parameters.

[MinimumAttribute](DSharpPlus.SlashCommands.MinimumAttribute.md)

Sets a minimum value for this slash command option. Only valid for <xref href="System.Int64" data-throw-if-not-resolved="false"></xref> or <xref href="System.Double" data-throw-if-not-resolved="false"></xref> parameters.

[MinimumLengthAttribute](DSharpPlus.SlashCommands.MinimumLengthAttribute.md)

Sets a minimum allowed length for this slash command option. Only valid for <xref href="System.String" data-throw-if-not-resolved="false"></xref> parameters.

[NameLocalizationAttribute](DSharpPlus.SlashCommands.NameLocalizationAttribute.md)

Specifies a locale for a slash command name. The longest name is the name that counts toward character limits.

[OptionAttribute](DSharpPlus.SlashCommands.OptionAttribute.md)

Marks this parameter as an option for a slash command.

[SlashCheckBaseAttribute](DSharpPlus.SlashCommands.SlashCheckBaseAttribute.md)

The base class for a pre-execution check for a slash command.

[SlashCommandAttribute](DSharpPlus.SlashCommands.SlashCommandAttribute.md)

Marks this method as a slash command.

[SlashCommandGroupAttribute](DSharpPlus.SlashCommands.SlashCommandGroupAttribute.md)

Marks this class a slash command group.

[SlashCommandPermissionsAttribute](DSharpPlus.SlashCommands.SlashCommandPermissionsAttribute.md)

[SlashCommandsConfiguration](DSharpPlus.SlashCommands.SlashCommandsConfiguration.md)

A configuration for a <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension" data-throw-if-not-resolved="false"></xref>.

[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)

A class that handles slash commands for a client.

[SlashExecutionChecksFailedException](DSharpPlus.SlashCommands.SlashExecutionChecksFailedException.md)

Thrown when a pre-execution check for a slash command fails.

[SlashModuleLifespanAttribute](DSharpPlus.SlashCommands.SlashModuleLifespanAttribute.md)

Defines this slash command module's lifespan. Module lifespans are transient by default.

### Interfaces

[IAutocompleteProvider](DSharpPlus.SlashCommands.IAutocompleteProvider.md)

All autocomplete providers must inherit from this interface.

[IChoiceProvider](DSharpPlus.SlashCommands.IChoiceProvider.md)

All choice providers must inherit from this interface.

### Enums

[Localization](DSharpPlus.SlashCommands.Localization.md)

Supported locals for slash command localizations.

[SlashModuleLifespan](DSharpPlus.SlashCommands.SlashModuleLifespan.md)

Represents a slash command module lifespan.

