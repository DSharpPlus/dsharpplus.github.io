# Class CommandModuleBuilder

Namespace: [DSharpPlus.CommandsNext.Builders](DSharpPlus.CommandsNext.Builders.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents an interface to build a command module.

```csharp
public sealed class CommandModuleBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandModuleBuilder](DSharpPlus.CommandsNext.Builders.CommandModuleBuilder.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Builders_CommandModuleBuilder__ctor"></a>CommandModuleBuilder\(\)

Creates a new command module builder.

```csharp
public CommandModuleBuilder()
```

## Properties

### <a id="DSharpPlus_CommandsNext_Builders_CommandModuleBuilder_Lifespan"></a>Lifespan

Gets the lifespan for the built module.

```csharp
public ModuleLifespan Lifespan { get; }
```

#### Property Value

[ModuleLifespan](DSharpPlus.CommandsNext.Attributes.ModuleLifespan.md)

### <a id="DSharpPlus_CommandsNext_Builders_CommandModuleBuilder_Type"></a>Type

Gets the type this build will construct a module out of.

```csharp
public Type Type { get; }
```

#### Property Value

[Type](https://learn.microsoft.com/dotnet/api/system.type)

## Methods

### <a id="DSharpPlus_CommandsNext_Builders_CommandModuleBuilder_WithLifespan_DSharpPlus_CommandsNext_Attributes_ModuleLifespan_"></a>WithLifespan\(ModuleLifespan\)

Lifespan to give this module.

```csharp
public CommandModuleBuilder WithLifespan(ModuleLifespan lifespan)
```

#### Parameters

`lifespan` [ModuleLifespan](DSharpPlus.CommandsNext.Attributes.ModuleLifespan.md)

Lifespan for this module.

#### Returns

[CommandModuleBuilder](DSharpPlus.CommandsNext.Builders.CommandModuleBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandModuleBuilder_WithType_System_Type_"></a>WithType\(Type\)

Sets the type this builder will construct a module out of.

```csharp
public CommandModuleBuilder WithType(Type t)
```

#### Parameters

`t` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type to build a module out of. It has to derive from <xref href="DSharpPlus.CommandsNext.BaseCommandModule" data-throw-if-not-resolved="false"></xref>.

#### Returns

[CommandModuleBuilder](DSharpPlus.CommandsNext.Builders.CommandModuleBuilder.md)

This builder.

