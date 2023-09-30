# Class CommandGroupBuilder

Namespace: [DSharpPlus.CommandsNext.Builders](DSharpPlus.CommandsNext.Builders.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents an interface to build a command group.

```csharp
public sealed class CommandGroupBuilder : CommandBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md) ← 
[CommandGroupBuilder](DSharpPlus.CommandsNext.Builders.CommandGroupBuilder.md)

###### Inherited Members

[CommandBuilder.Name](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_Name), 
[CommandBuilder.Category](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_Category), 
[CommandBuilder.Aliases](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_Aliases), 
[CommandBuilder.Description](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_Description), 
[CommandBuilder.IsHidden](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_IsHidden), 
[CommandBuilder.ExecutionChecks](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_ExecutionChecks), 
[CommandBuilder.Overloads](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_Overloads), 
[CommandBuilder.Module](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_Module), 
[CommandBuilder.CustomAttributes](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_CustomAttributes), 
[CommandBuilder.WithName\(string\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithName\_System\_String\_), 
[CommandBuilder.WithCategory\(string?\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithCategory\_System\_String\_), 
[CommandBuilder.WithAliases\(params string\[\]\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithAliases\_System\_String\_\_\_), 
[CommandBuilder.WithAlias\(string\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithAlias\_System\_String\_), 
[CommandBuilder.WithDescription\(string\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithDescription\_System\_String\_), 
[CommandBuilder.WithHiddenStatus\(bool\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithHiddenStatus\_System\_Boolean\_), 
[CommandBuilder.WithExecutionChecks\(params CheckBaseAttribute\[\]\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithExecutionChecks\_DSharpPlus\_CommandsNext\_Attributes\_CheckBaseAttribute\_\_\_), 
[CommandBuilder.WithExecutionCheck\(CheckBaseAttribute\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithExecutionCheck\_DSharpPlus\_CommandsNext\_Attributes\_CheckBaseAttribute\_), 
[CommandBuilder.WithOverloads\(params CommandOverloadBuilder\[\]\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithOverloads\_DSharpPlus\_CommandsNext\_Builders\_CommandOverloadBuilder\_\_\_), 
[CommandBuilder.WithOverload\(CommandOverloadBuilder\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithOverload\_DSharpPlus\_CommandsNext\_Builders\_CommandOverloadBuilder\_), 
[CommandBuilder.WithCustomAttribute\(Attribute\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithCustomAttribute\_System\_Attribute\_), 
[CommandBuilder.WithCustomAttributes\(params Attribute\[\]\)](DSharpPlus.CommandsNext.Builders.CommandBuilder.md\#DSharpPlus\_CommandsNext\_Builders\_CommandBuilder\_WithCustomAttributes\_System\_Attribute\_\_\_)

## Constructors

### <a id="DSharpPlus_CommandsNext_Builders_CommandGroupBuilder__ctor"></a>CommandGroupBuilder\(\)

Creates a new module-less command group builder.

```csharp
public CommandGroupBuilder()
```

### <a id="DSharpPlus_CommandsNext_Builders_CommandGroupBuilder__ctor_DSharpPlus_CommandsNext_Entities_ICommandModule_"></a>CommandGroupBuilder\(ICommandModule?\)

Creates a new command group builder.

```csharp
public CommandGroupBuilder(ICommandModule? module)
```

#### Parameters

`module` [ICommandModule](DSharpPlus.CommandsNext.Entities.ICommandModule.md)?

Module on which this group is to be defined.

## Properties

### <a id="DSharpPlus_CommandsNext_Builders_CommandGroupBuilder_Children"></a>Children

Gets the list of child commands registered for this group.

```csharp
public IReadOnlyList<CommandBuilder> Children { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)\>

## Methods

### <a id="DSharpPlus_CommandsNext_Builders_CommandGroupBuilder_WithChild_DSharpPlus_CommandsNext_Builders_CommandBuilder_"></a>WithChild\(CommandBuilder\)

Adds a command to the collection of child commands for this group.

```csharp
public CommandGroupBuilder WithChild(CommandBuilder child)
```

#### Parameters

`child` [CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)

Command to add to the collection of child commands for this group.

#### Returns

[CommandGroupBuilder](DSharpPlus.CommandsNext.Builders.CommandGroupBuilder.md)

This builder.

