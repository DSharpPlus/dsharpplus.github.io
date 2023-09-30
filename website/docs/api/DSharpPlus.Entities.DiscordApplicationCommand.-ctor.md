# Constructor DiscordApplicationCommand

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordApplicationCommand__ctor_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandOption__System_Nullable_System_Boolean__DSharpPlus_ApplicationCommandType_System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Nullable_System_Boolean__System_Nullable_DSharpPlus_Permissions__System_Nullable_System_Boolean__"></a>DiscordApplicationCommand\(string, string, IEnumerable<DiscordApplicationCommandOption\>, bool?, ApplicationCommandType, IReadOnlyDictionary<string, string\>, IReadOnlyDictionary<string, string\>, bool?, Permissions?, bool?\)

Creates a new instance of a <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordApplicationCommand(string name, string description, IEnumerable<DiscordApplicationCommandOption> options = null, bool? defaultPermission = null, ApplicationCommandType type = ApplicationCommandType.SlashCommand, IReadOnlyDictionary<string, string> name_localizations = null, IReadOnlyDictionary<string, string> description_localizations = null, bool? allowDMUsage = null, Permissions? defaultMemberPermissions = null, bool? nsfw = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the command.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the command.

`options` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandOption](DSharpPlus.Entities.DiscordApplicationCommandOption.md)\>

Optional parameters for this command.

`defaultPermission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the command is enabled by default when the application is added to a guild.

`type` [ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

The type of the application command

`name\_localizations` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Localization dictionary for <code class="paramref">name</code> field. Values follow the same restrictions as <code class="paramref">name</code>.

`description\_localizations` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Localization dictionary for <code class="paramref">description</code> field. Values follow the same restrictions as <code class="paramref">description</code>.

`allowDMUsage` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this command can be invoked in DMs.

`defaultMemberPermissions` [Permissions](DSharpPlus.Permissions.md)?

What permissions this command requires to be invoked.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the command is age restricted.

