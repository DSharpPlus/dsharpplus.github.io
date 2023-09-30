# Class Command

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a command.

```csharp
public class Command
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Command](DSharpPlus.CommandsNext.Command.md)

###### Derived

[CommandGroup](DSharpPlus.CommandsNext.CommandGroup.md)

## Properties

### <a id="DSharpPlus_CommandsNext_Command_Aliases"></a>Aliases

Gets this command's aliases.

```csharp
public IReadOnlyList<string> Aliases { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_CommandsNext_Command_Category"></a>Category

Gets the category this command belongs to.

```csharp
public string? Category { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_CommandsNext_Command_CustomAttributes"></a>CustomAttributes

Gets the custom attributes defined on this command.

```csharp
public IReadOnlyList<Attribute> CustomAttributes { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[Attribute](https://learn.microsoft.com/dotnet/api/system.attribute)\>

### <a id="DSharpPlus_CommandsNext_Command_Description"></a>Description

Gets this command's description.

```csharp
public string? Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_CommandsNext_Command_ExecutionChecks"></a>ExecutionChecks

Gets a collection of pre-execution checks for this command.

```csharp
public IReadOnlyList<CheckBaseAttribute> ExecutionChecks { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>

### <a id="DSharpPlus_CommandsNext_Command_IsHidden"></a>IsHidden

Gets whether this command is hidden.

```csharp
public bool IsHidden { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_CommandsNext_Command_Module"></a>Module

Gets the module in which this command is defined.

```csharp
public ICommandModule? Module { get; }
```

#### Property Value

[ICommandModule](DSharpPlus.CommandsNext.Entities.ICommandModule.md)?

### <a id="DSharpPlus_CommandsNext_Command_Name"></a>Name

Gets this command's name.

```csharp
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_CommandsNext_Command_Overloads"></a>Overloads

Gets a collection of this command's overloads.

```csharp
public IReadOnlyList<CommandOverload> Overloads { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CommandOverload](DSharpPlus.CommandsNext.CommandOverload.md)\>

### <a id="DSharpPlus_CommandsNext_Command_Parent"></a>Parent

Gets this command's parent module, if any.

```csharp
public CommandGroup? Parent { get; }
```

#### Property Value

[CommandGroup](DSharpPlus.CommandsNext.CommandGroup.md)?

### <a id="DSharpPlus_CommandsNext_Command_QualifiedName"></a>QualifiedName

Gets this command's qualified name (i.e. one that includes all module names).

```csharp
public string QualifiedName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_CommandsNext_Command_Equals_System_Object_"></a>Equals\(object?\)

Checks whether this command equals another object.

```csharp
public override bool Equals(object? obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)?

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this command is equal to another object.

### <a id="DSharpPlus_CommandsNext_Command_ExecuteAsync_DSharpPlus_CommandsNext_CommandContext_"></a>ExecuteAsync\(CommandContext\)

Executes this command with specified context.

```csharp
public virtual Task<CommandResult> ExecuteAsync(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context to execute the command in.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[CommandResult](DSharpPlus.CommandsNext.CommandResult.md)\>

Command's execution results.

### <a id="DSharpPlus_CommandsNext_Command_GetHashCode"></a>GetHashCode\(\)

Gets this command's hash code.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

This command's hash code.

### <a id="DSharpPlus_CommandsNext_Command_RunChecksAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>RunChecksAsync\(CommandContext, bool\)

Runs pre-execution checks for this command and returns any that fail for given context.

```csharp
public Task<IEnumerable<CheckBaseAttribute>> RunChecksAsync(CommandContext ctx, bool help)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the command is executed.

`help` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this check is being executed from help or not. This can be used to probe whether command can be run without setting off certain fail conditions (such as cooldowns).

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>\>

Pre-execution checks that fail for given context.

### <a id="DSharpPlus_CommandsNext_Command_ToString"></a>ToString\(\)

Returns a string representation of this command.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this command.

## Operators

### <a id="DSharpPlus_CommandsNext_Command_op_Equality_DSharpPlus_CommandsNext_Command_DSharpPlus_CommandsNext_Command_"></a>operator ==\(Command?, Command?\)

Checks whether this command is equal to another one.

```csharp
public static bool operator ==(Command? cmd1, Command? cmd2)
```

#### Parameters

`cmd1` [Command](DSharpPlus.CommandsNext.Command.md)?

Command to compare to.

`cmd2` [Command](DSharpPlus.CommandsNext.Command.md)?

Command to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two commands are equal.

### <a id="DSharpPlus_CommandsNext_Command_op_Inequality_DSharpPlus_CommandsNext_Command_DSharpPlus_CommandsNext_Command_"></a>operator \!=\(Command?, Command?\)

Checks whether this command is not equal to another one.

```csharp
public static bool operator !=(Command? cmd1, Command? cmd2)
```

#### Parameters

`cmd1` [Command](DSharpPlus.CommandsNext.Command.md)?

Command to compare to.

`cmd2` [Command](DSharpPlus.CommandsNext.Command.md)?

Command to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two commands are not equal.

