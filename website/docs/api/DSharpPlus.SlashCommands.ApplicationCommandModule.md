# Class ApplicationCommandModule

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents a base class for slash command modules.

```csharp
public abstract class ApplicationCommandModule
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ApplicationCommandModule](DSharpPlus.SlashCommands.ApplicationCommandModule.md)

## Methods

### <a id="DSharpPlus_SlashCommands_ApplicationCommandModule_AfterContextMenuExecutionAsync_DSharpPlus_SlashCommands_ContextMenuContext_"></a>AfterContextMenuExecutionAsync\(ContextMenuContext\)

Called after the execution of a context menu in the module.

```csharp
public virtual Task AfterContextMenuExecutionAsync(ContextMenuContext ctx)
```

#### Parameters

`ctx` [ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md)

The context.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_ApplicationCommandModule_AfterSlashExecutionAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>AfterSlashExecutionAsync\(InteractionContext\)

Called after the execution of a slash command in the module.

```csharp
public virtual Task AfterSlashExecutionAsync(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

The context.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_ApplicationCommandModule_BeforeContextMenuExecutionAsync_DSharpPlus_SlashCommands_ContextMenuContext_"></a>BeforeContextMenuExecutionAsync\(ContextMenuContext\)

Called before the execution of a context menu in the module.

```csharp
public virtual Task<bool> BeforeContextMenuExecutionAsync(ContextMenuContext ctx)
```

#### Parameters

`ctx` [ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md)

The context.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether or not to execute the slash command.

### <a id="DSharpPlus_SlashCommands_ApplicationCommandModule_BeforeSlashExecutionAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>BeforeSlashExecutionAsync\(InteractionContext\)

Called before the execution of a slash command in the module.

```csharp
public virtual Task<bool> BeforeSlashExecutionAsync(InteractionContext ctx)
```

#### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

The context.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether or not to execute the slash command.

