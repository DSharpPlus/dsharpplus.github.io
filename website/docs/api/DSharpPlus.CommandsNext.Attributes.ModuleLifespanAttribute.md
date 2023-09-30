# Class ModuleLifespanAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines a lifespan for this command module.

```csharp
[AttributeUsage(AttributeTargets.Class, AllowMultiple = false, Inherited = false)]
public class ModuleLifespanAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[ModuleLifespanAttribute](DSharpPlus.CommandsNext.Attributes.ModuleLifespanAttribute.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Attributes_ModuleLifespanAttribute__ctor_DSharpPlus_CommandsNext_Attributes_ModuleLifespan_"></a>ModuleLifespanAttribute\(ModuleLifespan\)

Defines a lifespan for this command module.

```csharp
public ModuleLifespanAttribute(ModuleLifespan lifespan)
```

#### Parameters

`lifespan` [ModuleLifespan](DSharpPlus.CommandsNext.Attributes.ModuleLifespan.md)

Lifespan for this module.

## Properties

### <a id="DSharpPlus_CommandsNext_Attributes_ModuleLifespanAttribute_Lifespan"></a>Lifespan

Gets the lifespan defined for this module.

```csharp
public ModuleLifespan Lifespan { get; }
```

#### Property Value

[ModuleLifespan](DSharpPlus.CommandsNext.Attributes.ModuleLifespan.md)

