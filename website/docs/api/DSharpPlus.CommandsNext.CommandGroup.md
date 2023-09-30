# Class CommandGroup

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a command group.

```csharp
public class CommandGroup : Command
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Command](DSharpPlus.CommandsNext.Command.md) ← 
[CommandGroup](DSharpPlus.CommandsNext.CommandGroup.md)

###### Inherited Members

[Command.Name](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Name), 
[Command.Category](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Category), 
[Command.QualifiedName](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_QualifiedName), 
[Command.Aliases](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Aliases), 
[Command.Parent](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Parent), 
[Command.Description](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Description), 
[Command.IsHidden](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_IsHidden), 
[Command.ExecutionChecks](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_ExecutionChecks), 
[Command.Overloads](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Overloads), 
[Command.Module](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Module), 
[Command.CustomAttributes](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_CustomAttributes), 
[Command.ExecuteAsync\(CommandContext\)](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_ExecuteAsync\_DSharpPlus\_CommandsNext\_CommandContext\_), 
[Command.RunChecksAsync\(CommandContext, bool\)](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_RunChecksAsync\_DSharpPlus\_CommandsNext\_CommandContext\_System\_Boolean\_), 
[Command.Equals\(object?\)](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_Equals\_System\_Object\_), 
[Command.GetHashCode\(\)](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_GetHashCode), 
[Command.ToString\(\)](DSharpPlus.CommandsNext.Command.md\#DSharpPlus\_CommandsNext\_Command\_ToString)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandGroup_Children"></a>Children

Gets all the commands that belong to this module.

```csharp
public IReadOnlyList<Command> Children { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[Command](DSharpPlus.CommandsNext.Command.md)\>

### <a id="DSharpPlus_CommandsNext_CommandGroup_IsExecutableWithoutSubcommands"></a>IsExecutableWithoutSubcommands

Gets whether this command is executable without subcommands.

```csharp
public bool IsExecutableWithoutSubcommands { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

## Methods

### <a id="DSharpPlus_CommandsNext_CommandGroup_ExecuteAsync_DSharpPlus_CommandsNext_CommandContext_"></a>ExecuteAsync\(CommandContext\)

Executes this command or its subcommand with specified context.

```csharp
public override Task<CommandResult> ExecuteAsync(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context to execute the command in.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[CommandResult](DSharpPlus.CommandsNext.CommandResult.md)\>

Command's execution results.

