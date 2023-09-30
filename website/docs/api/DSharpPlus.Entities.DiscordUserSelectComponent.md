# Class DiscordUserSelectComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

A select component that allows users to be selected.

```csharp
public sealed class DiscordUserSelectComponent : BaseDiscordSelectComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md) ← 
[BaseDiscordSelectComponent](DSharpPlus.Entities.BaseDiscordSelectComponent.md) ← 
[DiscordUserSelectComponent](DSharpPlus.Entities.DiscordUserSelectComponent.md)

###### Inherited Members

[BaseDiscordSelectComponent.Placeholder](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_Placeholder), 
[BaseDiscordSelectComponent.Disabled](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_Disabled), 
[BaseDiscordSelectComponent.MinimumSelectedValues](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_MinimumSelectedValues), 
[BaseDiscordSelectComponent.MaximumSelectedValues](DSharpPlus.Entities.BaseDiscordSelectComponent.md\#DSharpPlus\_Entities\_BaseDiscordSelectComponent\_MaximumSelectedValues), 
[DiscordComponent.Type](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_Type), 
[DiscordComponent.CustomId](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_CustomId)

## Constructors

### <a id="DSharpPlus_Entities_DiscordUserSelectComponent__ctor_System_String_System_String_System_Boolean_System_Int32_System_Int32_"></a>DiscordUserSelectComponent\(string, string, bool, int, int\)

Creates a new user select component.

```csharp
public DiscordUserSelectComponent(string customId, string placeholder, bool disabled = false, int minOptions = 1, int maxOptions = 1)
```

#### Parameters

`customId` [string](https://learn.microsoft.com/dotnet/api/system.string)

The ID of this component.

`placeholder` [string](https://learn.microsoft.com/dotnet/api/system.string)

Placeholder text that's shown when no options are selected.

`disabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this component is disabled.

`minOptions` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The minimum amount of options to be selected.

`maxOptions` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The maximum amount of options to be selected, up to 25.

## Methods

### <a id="DSharpPlus_Entities_DiscordUserSelectComponent_Disable"></a>Disable\(\)

Disables this component.

```csharp
public DiscordUserSelectComponent Disable()
```

#### Returns

[DiscordUserSelectComponent](DSharpPlus.Entities.DiscordUserSelectComponent.md)

The current component.

### <a id="DSharpPlus_Entities_DiscordUserSelectComponent_Enable"></a>Enable\(\)

Enables this component.

```csharp
public DiscordUserSelectComponent Enable()
```

#### Returns

[DiscordUserSelectComponent](DSharpPlus.Entities.DiscordUserSelectComponent.md)

The current component.
