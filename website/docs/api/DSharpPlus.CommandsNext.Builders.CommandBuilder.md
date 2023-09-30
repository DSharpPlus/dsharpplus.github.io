# Class CommandBuilder

Namespace: [DSharpPlus.CommandsNext.Builders](DSharpPlus.CommandsNext.Builders.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents an interface to build a command.

```csharp
public class CommandBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

###### Derived

[CommandGroupBuilder](DSharpPlus.CommandsNext.Builders.CommandGroupBuilder.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder__ctor"></a>CommandBuilder\(\)

Creates a new module-less command builder.

```csharp
public CommandBuilder()
```

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder__ctor_DSharpPlus_CommandsNext_Entities_ICommandModule_"></a>CommandBuilder\(ICommandModule?\)

Creates a new command builder.

```csharp
public CommandBuilder(ICommandModule? module)
```

#### Parameters

`module` [ICommandModule](DSharpPlus.CommandsNext.Entities.ICommandModule.md)?

Module on which this command is to be defined.

## Properties

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_Aliases"></a>Aliases

Gets the aliases set for this command.

```csharp
public IReadOnlyList<string> Aliases { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_Category"></a>Category

Gets the category set for this command.

```csharp
public string? Category { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_CustomAttributes"></a>CustomAttributes

Gets custom attributes defined on this command.

```csharp
public IReadOnlyList<Attribute> CustomAttributes { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute)\>

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_Description"></a>Description

Gets the description set for this command.

```csharp
public string? Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_ExecutionChecks"></a>ExecutionChecks

Gets the execution checks defined for this command.

```csharp
public IReadOnlyList<CheckBaseAttribute> ExecutionChecks { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_IsHidden"></a>IsHidden

Gets whether this command will be hidden or not.

```csharp
public bool IsHidden { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_Module"></a>Module

Gets the module on which this command is to be defined.

```csharp
public ICommandModule? Module { get; }
```

#### Property Value

[ICommandModule](DSharpPlus.CommandsNext.Entities.ICommandModule.md)?

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_Name"></a>Name

Gets the name set for this command.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_Overloads"></a>Overloads

Gets the collection of this command's overloads.

```csharp
public IReadOnlyList<CommandOverloadBuilder> Overloads { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CommandOverloadBuilder](DSharpPlus.CommandsNext.Builders.CommandOverloadBuilder.md)\>

## Methods

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithAlias_System_String_"></a>WithAlias\(string\)

Adds an alias to this command.

```csharp
public CommandBuilder WithAlias(string alias)
```

#### Parameters

`alias` [string](https://learn.microsoft.com/dotnet/api/system.string)

Alias to add to the command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithAliases_System_String___"></a>WithAliases\(params string\[\]\)

Adds aliases to this command.

```csharp
public CommandBuilder WithAliases(params string[] aliases)
```

#### Parameters

`aliases` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

Aliases to add to the command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithCategory_System_String_"></a>WithCategory\(string?\)

Sets the category for this command.

```csharp
public CommandBuilder WithCategory(string? category)
```

#### Parameters

`category` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Category for this command. May be <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a>.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithCustomAttribute_System_Attribute_"></a>WithCustomAttribute\(Attribute\)

Adds a custom attribute to this command. This can be used to indicate various custom information about a command.

```csharp
public CommandBuilder WithCustomAttribute(Attribute attribute)
```

#### Parameters

`attribute` [Attribute](https://learn.microsoft.com/dotnet/api/system.attribute)

Attribute to add.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithCustomAttributes_System_Attribute___"></a>WithCustomAttributes\(params Attribute\[\]\)

Adds multiple custom attributes to this command. This can be used to indicate various custom information about a command.

```csharp
public CommandBuilder WithCustomAttributes(params Attribute[] attributes)
```

#### Parameters

`attributes` [Attribute](https://learn.microsoft.com/dotnet/api/system.attribute)\[\]

Attributes to add.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithDescription_System_String_"></a>WithDescription\(string\)

Sets the description for this command.

```csharp
public CommandBuilder WithDescription(string description)
```

#### Parameters

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description to use for this command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithExecutionCheck_DSharpPlus_CommandsNext_Attributes_CheckBaseAttribute_"></a>WithExecutionCheck\(CheckBaseAttribute\)

Adds a pre-execution check to this command.

```csharp
public CommandBuilder WithExecutionCheck(CheckBaseAttribute check)
```

#### Parameters

`check` [CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)

Pre-execution check to add to this command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithExecutionChecks_DSharpPlus_CommandsNext_Attributes_CheckBaseAttribute___"></a>WithExecutionChecks\(params CheckBaseAttribute\[\]\)

Adds pre-execution checks to this command.

```csharp
public CommandBuilder WithExecutionChecks(params CheckBaseAttribute[] checks)
```

#### Parameters

`checks` [CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\[\]

Pre-execution checks to add to this command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithHiddenStatus_System_Boolean_"></a>WithHiddenStatus\(bool\)

Sets whether this command is to be hidden.

```csharp
public CommandBuilder WithHiddenStatus(bool hidden)
```

#### Parameters

`hidden` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the command is to be hidden.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithName_System_String_"></a>WithName\(string\)

Sets the name for this command.

```csharp
public CommandBuilder WithName(string name)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name for this command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithOverload_DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder_"></a>WithOverload\(CommandOverloadBuilder\)

Adds an overload to this command. An executable command needs to have at least one overload.

```csharp
public CommandBuilder WithOverload(CommandOverloadBuilder overload)
```

#### Parameters

`overload` [CommandOverloadBuilder](DSharpPlus.CommandsNext.Builders.CommandOverloadBuilder.md)

Overload to add to this command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

### <a id="DSharpPlus_CommandsNext_Builders_CommandBuilder_WithOverloads_DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder___"></a>WithOverloads\(params CommandOverloadBuilder\[\]\)

Adds overloads to this command. An executable command needs to have at least one overload.

```csharp
public CommandBuilder WithOverloads(params CommandOverloadBuilder[] overloads)
```

#### Parameters

`overloads` [CommandOverloadBuilder](DSharpPlus.CommandsNext.Builders.CommandOverloadBuilder.md)\[\]

Overloads to add to this command.

#### Returns

[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

This builder.

