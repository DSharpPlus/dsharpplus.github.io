# Namespace DSharpPlus.CommandsNext.Attributes

### Classes

[AliasesAttribute](DSharpPlus.CommandsNext.Attributes.AliasesAttribute.md)

Adds aliases to this command or group.

[CategoryAttribute](DSharpPlus.CommandsNext.Attributes.CategoryAttribute.md)

[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)

Represents a base for all command pre-execution check attributes.

[CommandAttribute](DSharpPlus.CommandsNext.Attributes.CommandAttribute.md)

Marks this method as a command.

[CommandCooldownBucket](DSharpPlus.CommandsNext.Attributes.CommandCooldownBucket.md)

Represents a cooldown bucket for commands.

[CooldownAttribute](DSharpPlus.CommandsNext.Attributes.CooldownAttribute.md)

Defines a cooldown for this command. This allows you to define how many times can users execute a specific command

[DescriptionAttribute](DSharpPlus.CommandsNext.Attributes.DescriptionAttribute.md)

Gives this command, group, or argument a description, which is used when listing help.

[DontInjectAttribute](DSharpPlus.CommandsNext.Attributes.DontInjectAttribute.md)

Prevents this field or property from having its value injected by dependency injection.

[GroupAttribute](DSharpPlus.CommandsNext.Attributes.GroupAttribute.md)

Marks this class as a command group.

[GroupCommandAttribute](DSharpPlus.CommandsNext.Attributes.GroupCommandAttribute.md)

Marks this method as a group command.

[HiddenAttribute](DSharpPlus.CommandsNext.Attributes.HiddenAttribute.md)

Marks this command or group as hidden.

[ModuleLifespanAttribute](DSharpPlus.CommandsNext.Attributes.ModuleLifespanAttribute.md)

Defines a lifespan for this command module.

[PriorityAttribute](DSharpPlus.CommandsNext.Attributes.PriorityAttribute.md)

Defines this command overload's priority. This determines the order in which overloads will be attempted to be called. Commands will be attempted in order of priority, in descending order.

[RemainingTextAttribute](DSharpPlus.CommandsNext.Attributes.RemainingTextAttribute.md)

Indicates that the command argument takes the rest of the input without parsing.

[RequireBotPermissionsAttribute](DSharpPlus.CommandsNext.Attributes.RequireBotPermissionsAttribute.md)

Defines that usage of this command is only possible when the bot is granted a specific permission.

[RequireDirectMessageAttribute](DSharpPlus.CommandsNext.Attributes.RequireDirectMessageAttribute.md)

Defines that a command is only usable within a direct message channel.

[RequireGuildAttribute](DSharpPlus.CommandsNext.Attributes.RequireGuildAttribute.md)

Defines that a command is only usable within a guild.

[RequireNsfwAttribute](DSharpPlus.CommandsNext.Attributes.RequireNsfwAttribute.md)

Defines that usage of this command is restricted to NSFW channels.

[RequireOwnerAttribute](DSharpPlus.CommandsNext.Attributes.RequireOwnerAttribute.md)

Defines that usage of this command is restricted to the owner of the bot.

[RequirePermissionsAttribute](DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute.md)

Defines that usage of this command is restricted to members with specified permissions. This check also verifies that the bot has the same permissions.

[RequirePrefixesAttribute](DSharpPlus.CommandsNext.Attributes.RequirePrefixesAttribute.md)

Defines that usage of this command is only allowed with specific prefixes.

[RequireReferencedMessageAttribute](DSharpPlus.CommandsNext.Attributes.RequireReferencedMessageAttribute.md)

Defines that a command is only usable when sent in reply. Command will appear in help regardless of this attribute.

[RequireRolesAttribute](DSharpPlus.CommandsNext.Attributes.RequireRolesAttribute.md)

Defines that usage of this command is restricted to members with specified role. Note that it's much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

[RequireUserPermissionsAttribute](DSharpPlus.CommandsNext.Attributes.RequireUserPermissionsAttribute.md)

Defines that usage of this command is restricted to members with specified permissions.

### Enums

[CooldownBucketType](DSharpPlus.CommandsNext.Attributes.CooldownBucketType.md)

Defines how are command cooldowns applied.

[ModuleLifespan](DSharpPlus.CommandsNext.Attributes.ModuleLifespan.md)

Defines lifespan of a command module.

[RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

Specifies how <xref href="DSharpPlus.CommandsNext.Attributes.RequireRolesAttribute" data-throw-if-not-resolved="false"></xref> checks for roles.

