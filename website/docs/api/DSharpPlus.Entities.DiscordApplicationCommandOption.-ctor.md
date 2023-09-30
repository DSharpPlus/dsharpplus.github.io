# Constructor DiscordApplicationCommandOption

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordApplicationCommandOption__ctor_System_String_System_String_DSharpPlus_ApplicationCommandOptionType_System_Nullable_System_Boolean__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandOptionChoice__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandOption__System_Collections_Generic_IEnumerable_DSharpPlus_ChannelType__System_Nullable_System_Boolean__System_Object_System_Object_System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Nullable_System_Int32__System_Nullable_System_Int32__"></a>DiscordApplicationCommandOption\(string, string, ApplicationCommandOptionType, bool?, IEnumerable<DiscordApplicationCommandOptionChoice\>, IEnumerable<DiscordApplicationCommandOption\>, IEnumerable<ChannelType\>, bool?, object, object, IReadOnlyDictionary<string, string\>, IReadOnlyDictionary<string, string\>, int?, int?\)

Creates a new instance of a <xref href="DSharpPlus.Entities.DiscordApplicationCommandOption" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordApplicationCommandOption(string name, string description, ApplicationCommandOptionType type, bool? required = null, IEnumerable<DiscordApplicationCommandOptionChoice> choices = null, IEnumerable<DiscordApplicationCommandOption> options = null, IEnumerable<ChannelType> channelTypes = null, bool? autocomplete = null, object minValue = null, object maxValue = null, IReadOnlyDictionary<string, string> name_localizations = null, IReadOnlyDictionary<string, string> description_localizations = null, int? minLength = null, int? maxLength = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of this parameter.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the parameter.

`type` [ApplicationCommandOptionType](DSharpPlus.ApplicationCommandOptionType.md)

The type of this parameter.

`required` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the parameter is required.

`choices` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandOptionChoice](DSharpPlus.Entities.DiscordApplicationCommandOptionChoice.md)\>

The optional choice selection for this parameter.

`options` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandOption](DSharpPlus.Entities.DiscordApplicationCommandOption.md)\>

The optional subcommands for this parameter.

`channelTypes` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ChannelType](DSharpPlus.ChannelType.md)\>

The channel types to be restricted to for this parameter, if of type <xref href="DSharpPlus.ApplicationCommandOptionType.Channel" data-throw-if-not-resolved="false"></xref>.

`autocomplete` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this parameter is autocomplete. If true, <code class="paramref">choices</code> must not be provided.

`minValue` [object](https://learn.microsoft.com/dotnet/api/system.object)

The minimum value for this parameter. Only valid for types <xref href="DSharpPlus.ApplicationCommandOptionType.Integer" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.ApplicationCommandOptionType.Number" data-throw-if-not-resolved="false"></xref>.

`maxValue` [object](https://learn.microsoft.com/dotnet/api/system.object)

The maximum value for this parameter. Only valid for types <xref href="DSharpPlus.ApplicationCommandOptionType.Integer" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.ApplicationCommandOptionType.Number" data-throw-if-not-resolved="false"></xref>.

`name\_localizations` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Name localizations for this parameter.

`description\_localizations` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Description localizations for this parameter.

`minLength` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The minimum allowed length for this parameter. Only valid for type <xref href="DSharpPlus.ApplicationCommandOptionType.String" data-throw-if-not-resolved="false"></xref>.

`maxLength` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The maximum allowed length for this parameter. Only valid for type <xref href="DSharpPlus.ApplicationCommandOptionType.String" data-throw-if-not-resolved="false"></xref>.

