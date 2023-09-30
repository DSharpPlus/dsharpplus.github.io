# Class DiscordApplicationCommandOption

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a parameter for a <xref href="DSharpPlus.Entities.DiscordApplicationCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordApplicationCommandOption
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordApplicationCommandOption](DSharpPlus.Entities.DiscordApplicationCommandOption.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption__ctor_System_String_System_String_DSharpPlus_ApplicationCommandOptionType_System_Nullable_System_Boolean__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandOptionChoice__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandOption__System_Collections_Generic_IEnumerable_DSharpPlus_ChannelType__System_Nullable_System_Boolean__System_Object_System_Object_System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Collections_Generic_IReadOnlyDictionary_System_String_System_String__System_Nullable_System_Int32__System_Nullable_System_Int32__"></a>DiscordApplicationCommandOption\(string, string, ApplicationCommandOptionType, bool?, IEnumerable<DiscordApplicationCommandOptionChoice\>, IEnumerable<DiscordApplicationCommandOption\>, IEnumerable<ChannelType\>, bool?, object, object, IReadOnlyDictionary<string, string\>, IReadOnlyDictionary<string, string\>, int?, int?\)

Creates a new instance of a <xref href="DSharpPlus.Entities.DiscordApplicationCommandOption" data-throw-if-not-resolved="false"></xref>.

```csharp
public DiscordApplicationCommandOption(string name, string description, ApplicationCommandOptionType type, bool? required = null, IEnumerable<DiscordApplicationCommandOptionChoice> choices = null, IEnumerable<DiscordApplicationCommandOption> options = null, IEnumerable<ChannelType> channelTypes = null, bool? autocomplete = null, object minValue = null, object maxValue = null, IReadOnlyDictionary<string, string> name_localizations = null, IReadOnlyDictionary<string, string> description_localizations = null, int? minLength = null, int? maxLength = null)
```

#### Parameters

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

## Properties

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_AutoComplete"></a>AutoComplete

Gets whether this option will auto-complete.

```csharp
[JsonProperty("autocomplete")]
public bool? AutoComplete { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_ChannelTypes"></a>ChannelTypes

Gets the channel types this command parameter is restricted to, if of type <xref href="DSharpPlus.ApplicationCommandOptionType.Channel" data-throw-if-not-resolved="false"></xref>..

```csharp
[JsonProperty("channel_types", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyCollection<ChannelType> ChannelTypes { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[ChannelType](DSharpPlus.ChannelType.md)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_Choices"></a>Choices

Gets the optional choices for this command parameter. Not applicable for auto-complete options.

```csharp
[JsonProperty("choices", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyCollection<DiscordApplicationCommandOptionChoice> Choices { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordApplicationCommandOptionChoice](DSharpPlus.Entities.DiscordApplicationCommandOptionChoice.md)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_Description"></a>Description

Gets the description of this command parameter.

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_DescriptionLocalizations"></a>DescriptionLocalizations

Localized descriptions for this option.

```csharp
[JsonProperty("description_localizations", NullValueHandling = NullValueHandling.Include)]
public IReadOnlyDictionary<string, string> DescriptionLocalizations { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_MaxLength"></a>MaxLength

Gets the maximum allowed length for this slash command parameter.

```csharp
[JsonProperty("max_length", NullValueHandling = NullValueHandling.Ignore)]
public int? MaxLength { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_MaxValue"></a>MaxValue

Gets the maximum value for this slash command parameter.

```csharp
[JsonProperty("max_value", NullValueHandling = NullValueHandling.Ignore)]
public object MaxValue { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_MinLength"></a>MinLength

Gets the minimum allowed length for this slash command parameter.

```csharp
[JsonProperty("min_length", NullValueHandling = NullValueHandling.Ignore)]
public int? MinLength { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_MinValue"></a>MinValue

Gets the minimum value for this slash command parameter.

```csharp
[JsonProperty("min_value", NullValueHandling = NullValueHandling.Ignore)]
public object MinValue { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_Name"></a>Name

Gets the name of this command parameter.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_NameLocalizations"></a>NameLocalizations

Localized names for this option.

```csharp
[JsonProperty("name_localizations", NullValueHandling = NullValueHandling.Include)]
public IReadOnlyDictionary<string, string> NameLocalizations { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_Options"></a>Options

Gets the optional subcommand parameters for this parameter.

```csharp
[JsonProperty("options", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyCollection<DiscordApplicationCommandOption> Options { get; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordApplicationCommandOption](DSharpPlus.Entities.DiscordApplicationCommandOption.md)\>

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_Required"></a>Required

Gets whether this command parameter is required.

```csharp
[JsonProperty("required", NullValueHandling = NullValueHandling.Ignore)]
public bool? Required { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordApplicationCommandOption_Type"></a>Type

Gets the type of this command parameter.

```csharp
[JsonProperty("type")]
public ApplicationCommandOptionType Type { get; }
```

#### Property Value

[ApplicationCommandOptionType](DSharpPlus.ApplicationCommandOptionType.md)

