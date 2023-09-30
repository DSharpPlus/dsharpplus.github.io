# Class DiscordSelectComponentOption

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents options for <xref href="DSharpPlus.Entities.DiscordSelectComponent" data-throw-if-not-resolved="false"></xref>.

```csharp
public sealed class DiscordSelectComponentOption
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordSelectComponentOption](DSharpPlus.Entities.DiscordSelectComponentOption.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordSelectComponentOption__ctor_System_String_System_String_System_String_System_Boolean_DSharpPlus_Entities_DiscordComponentEmoji_"></a>DiscordSelectComponentOption\(string, string, string, bool, DiscordComponentEmoji\)

```csharp
public DiscordSelectComponentOption(string label, string value, string description = null, bool isDefault = false, DiscordComponentEmoji emoji = null)
```

#### Parameters

`label` [string](https://learn.microsoft.com/dotnet/api/system.string)

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

`isDefault` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

`emoji` [DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordSelectComponentOption_Default"></a>Default

Whether this option is default. If true, this option will be pre-selected. Defaults to false.

```csharp
[JsonProperty("default", NullValueHandling = NullValueHandling.Ignore)]
public bool Default { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordSelectComponentOption_Description"></a>Description

The description of this option. This is optional.

```csharp
[JsonProperty("description", NullValueHandling = NullValueHandling.Ignore)]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordSelectComponentOption_Emoji"></a>Emoji

The emoji of this option. This is optional.

```csharp
[JsonProperty("emoji", NullValueHandling = NullValueHandling.Ignore)]
public DiscordComponentEmoji Emoji { get; }
```

#### Property Value

[DiscordComponentEmoji](DSharpPlus.Entities.DiscordComponentEmoji.md)

### <a id="DSharpPlus_Entities_DiscordSelectComponentOption_Label"></a>Label

The label to add. This is required.

```csharp
[JsonProperty("label", NullValueHandling = NullValueHandling.Ignore)]
public string Label { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordSelectComponentOption_Value"></a>Value

The value of this option. Akin to the Custom Id of components.

```csharp
[JsonProperty("value", NullValueHandling = NullValueHandling.Ignore)]
public string Value { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

