# Class DiscordActionRowComponent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a row of components. Action rows can have up to five components.

```csharp
public sealed class DiscordActionRowComponent : DiscordComponent
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md) ← 
[DiscordActionRowComponent](DSharpPlus.Entities.DiscordActionRowComponent.md)

###### Inherited Members

[DiscordComponent.Type](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_Type), 
[DiscordComponent.CustomId](DSharpPlus.Entities.DiscordComponent.md\#DSharpPlus\_Entities\_DiscordComponent\_CustomId)

## Constructors

### <a id="DSharpPlus_Entities_DiscordActionRowComponent__ctor_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordComponent__"></a>DiscordActionRowComponent\(IEnumerable<DiscordComponent\>\)

```csharp
public DiscordActionRowComponent(IEnumerable<DiscordComponent> components)
```

#### Parameters

`components` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\>

## Properties

### <a id="DSharpPlus_Entities_DiscordActionRowComponent_Components"></a>Components

The components contained within the action row.

```csharp
public IReadOnlyCollection<DiscordComponent> Components { get; set; }
```

#### Property Value

[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordComponent](DSharpPlus.Entities.DiscordComponent.md)\>

