# Class SlashModuleLifespanAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Defines this slash command module's lifespan. Module lifespans are transient by default.

```csharp
[AttributeUsage(AttributeTargets.Class, AllowMultiple = false)]
public sealed class SlashModuleLifespanAttribute : Attribute
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute) ← 
[SlashModuleLifespanAttribute](DSharpPlus.SlashCommands.SlashModuleLifespanAttribute.md)

## Constructors

### <a id="DSharpPlus_SlashCommands_SlashModuleLifespanAttribute__ctor_DSharpPlus_SlashCommands_SlashModuleLifespan_"></a>SlashModuleLifespanAttribute\(SlashModuleLifespan\)

Defines this slash command module's lifespan.

```csharp
public SlashModuleLifespanAttribute(SlashModuleLifespan lifespan)
```

#### Parameters

`lifespan` [SlashModuleLifespan](DSharpPlus.SlashCommands.SlashModuleLifespan.md)

The lifespan of the module. Module lifespans are transient by default.

## Properties

### <a id="DSharpPlus_SlashCommands_SlashModuleLifespanAttribute_Lifespan"></a>Lifespan

Gets the lifespan.

```csharp
public SlashModuleLifespan Lifespan { get; }
```

#### Property Value

[SlashModuleLifespan](DSharpPlus.SlashCommands.SlashModuleLifespan.md)

