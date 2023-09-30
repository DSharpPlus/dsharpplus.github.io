# Class DiscordEmbedField

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a field inside a discord embed.

```csharp
public sealed class DiscordEmbedField
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordEmbedField](DSharpPlus.Entities.DiscordEmbedField.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordEmbedField_Inline"></a>Inline

Gets whether or not this field should display inline.

```csharp
[JsonProperty("inline", NullValueHandling = NullValueHandling.Ignore)]
public bool Inline { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordEmbedField_Name"></a>Name

Gets the name of the field.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordEmbedField_Value"></a>Value

Gets the value of the field.

```csharp
[JsonProperty("value", NullValueHandling = NullValueHandling.Ignore)]
public string Value { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

