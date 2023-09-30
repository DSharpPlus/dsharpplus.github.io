# Class BaseCommandModule

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a base class for all command modules.

```csharp
public abstract class BaseCommandModule
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseCommandModule](DSharpPlus.CommandsNext.BaseCommandModule.md)

###### Derived

[CommandsNextExtension.DefaultHelpModule](DSharpPlus.CommandsNext.CommandsNextExtension.DefaultHelpModule.md)

## Methods

### <a id="DSharpPlus_CommandsNext_BaseCommandModule_AfterExecutionAsync_DSharpPlus_CommandsNext_CommandContext_"></a>AfterExecutionAsync\(CommandContext\)

Called after a command in the implementing module is successfully executed.

```csharp
public virtual Task AfterExecutionAsync(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the method is being executed.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_CommandsNext_BaseCommandModule_BeforeExecutionAsync_DSharpPlus_CommandsNext_CommandContext_"></a>BeforeExecutionAsync\(CommandContext\)

Called before a command in the implementing module is executed.

```csharp
public virtual Task BeforeExecutionAsync(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the method is being executed.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

