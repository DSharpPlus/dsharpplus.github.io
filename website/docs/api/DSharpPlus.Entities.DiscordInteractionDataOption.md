# Class DiscordInteractionDataOption

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents parameters for interaction commands.

```csharp
public sealed class DiscordInteractionDataOption
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordInteractionDataOption](DSharpPlus.Entities.DiscordInteractionDataOption.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordInteractionDataOption_Focused"></a>Focused

If this is an autocomplete option: Whether this option is currently active.

```csharp
[JsonProperty("focused")]
public bool Focused { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordInteractionDataOption_Name"></a>Name

Gets the name of this interaction parameter.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInteractionDataOption_Options"></a>Options

Gets the additional parameters if this parameter is a subcommand.

```csharp
[JsonProperty("options", NullValueHandling = NullValueHandling.Ignore)]
public IEnumerable<DiscordInteractionDataOption> Options { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordInteractionDataOption](DSharpPlus.Entities.DiscordInteractionDataOption.md)\>

### <a id="DSharpPlus_Entities_DiscordInteractionDataOption_Type"></a>Type

Gets the type of this interaction parameter.

```csharp
[JsonProperty("type")]
public ApplicationCommandOptionType Type { get; }
```

#### Property Value

[ApplicationCommandOptionType](DSharpPlus.ApplicationCommandOptionType.md)

### <a id="DSharpPlus_Entities_DiscordInteractionDataOption_Value"></a>Value

Gets the value of this interaction parameter.
<p>This can be cast to a <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/integral-numeric-types">long</a>, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">bool</a>, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/reference-types">string</a>, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/floating-point-numeric-types">double</a> or <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/integral-numeric-types">ulong</a> depending on the <xref href="DSharpPlus.Entities.DiscordInteractionDataOption.Type" data-throw-if-not-resolved="false"></xref></p>

```csharp
[JsonIgnore]
public object Value { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)

