# Class BaseDiscordSelectComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a base class for all select-menus.

```csharp
public abstract class BaseDiscordSelectComponent : DiscordComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md) ← 
[BaseDiscordSelectComponent](DSharpPlus.Entities.BaseDiscordSelectComponent.md)

###### Derived

[DiscordChannelSelectComponent](DSharpPlus.Entities.DiscordChannelSelectComponent.md), 
[DiscordMentionableSelectComponent](DSharpPlus.Entities.DiscordMentionableSelectComponent.md), 
[DiscordRoleSelectComponent](DSharpPlus.Entities.DiscordRoleSelectComponent.md), 
[DiscordSelectComponent](DSharpPlus.Entities.DiscordSelectComponent.md), 
[DiscordUserSelectComponent](DSharpPlus.Entities.DiscordUserSelectComponent.md)

###### Inherited Members

[DiscordComponent.Type](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_Type), 
[DiscordComponent.CustomId](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_CustomId)

## Properties

### <a id="DSharpPlus_Entities_BaseDiscordSelectComponent_Disabled"></a>Disabled

Whether this dropdown can be interacted with.

```csharp
[JsonProperty("disabled", NullValueHandling = NullValueHandling.Ignore)]
public bool Disabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_BaseDiscordSelectComponent_MaximumSelectedValues"></a>MaximumSelectedValues

The maximum amount of options that can be selected. Must be greater than or equal to zero or <xref href="DSharpPlus.Entities.BaseDiscordSelectComponent.MinimumSelectedValues" data-throw-if-not-resolved="false"></xref>. Defaults to one.

```csharp
[JsonProperty("max_values", NullValueHandling = NullValueHandling.Ignore)]
public int? MaximumSelectedValues { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_BaseDiscordSelectComponent_MinimumSelectedValues"></a>MinimumSelectedValues

The minimum amount of options that can be selected. Must be less than or equal to <xref href="DSharpPlus.Entities.BaseDiscordSelectComponent.MaximumSelectedValues" data-throw-if-not-resolved="false"></xref>. Defaults to one.

```csharp
[JsonProperty("min_values", NullValueHandling = NullValueHandling.Ignore)]
public int? MinimumSelectedValues { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_BaseDiscordSelectComponent_Placeholder"></a>Placeholder

The text to show when no option is selected.

```csharp
[JsonProperty("placeholder", NullValueHandling = NullValueHandling.Ignore)]
public string Placeholder { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

