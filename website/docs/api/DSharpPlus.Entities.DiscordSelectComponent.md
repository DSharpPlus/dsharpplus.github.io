# Class DiscordSelectComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

A select menu with multiple options to choose from.

```csharp
public sealed class DiscordSelectComponent : BaseDiscordSelectComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md) ← 
[BaseDiscordSelectComponent](DSharpPlus.Entities.BaseDiscordSelectComponent.md) ← 
[DiscordSelectComponent](DSharpPlus.Entities.DiscordSelectComponent.md)

###### Inherited Members

[BaseDiscordSelectComponent.Placeholder](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_Placeholder), 
[BaseDiscordSelectComponent.Disabled](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_Disabled), 
[BaseDiscordSelectComponent.MinimumSelectedValues](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_MinimumSelectedValues), 
[BaseDiscordSelectComponent.MaximumSelectedValues](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_MaximumSelectedValues), 
[DiscordComponent.Type](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_Type), 
[DiscordComponent.CustomId](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_CustomId)

## Constructors

### <a id="DSharpPlus_Entities_DiscordSelectComponent__ctor_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordSelectComponentOption__System_Boolean_System_Int32_System_Int32_"></a>DiscordSelectComponent\(string, string, IEnumerable<DiscordSelectComponentOption\>, bool, int, int\)

```csharp
public DiscordSelectComponent(string customId, string placeholder, IEnumerable<DiscordSelectComponentOption> options, bool disabled = false, int minOptions = 1, int maxOptions = 1)
```

#### Parameters

`customId` [string](https://learn.microsoft.com/dotnet/api/system.string)

`placeholder` [string](https://learn.microsoft.com/dotnet/api/system.string)

`options` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordSelectComponentOption](DSharpPlus.Entities.DiscordSelectComponentOption.md)\>

`disabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

`minOptions` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`maxOptions` [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Properties

### <a id="DSharpPlus_Entities_DiscordSelectComponent_Options"></a>Options

The options to pick from on this component.

```csharp
[JsonProperty("options", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<DiscordSelectComponentOption> Options { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordSelectComponentOption](DSharpPlus.Entities.DiscordSelectComponentOption.md)\>

## Methods

### <a id="DSharpPlus_Entities_DiscordSelectComponent_Disable"></a>Disable\(\)

Disables this component.

```csharp
public DiscordSelectComponent Disable()
```

#### Returns

[DiscordSelectComponent](DSharpPlus.Entities.DiscordSelectComponent.md)

The current component.

### <a id="DSharpPlus_Entities_DiscordSelectComponent_Enable"></a>Enable\(\)

Enables this component.

```csharp
public DiscordSelectComponent Enable()
```

#### Returns

[DiscordSelectComponent](DSharpPlus.Entities.DiscordSelectComponent.md)

The current component.

