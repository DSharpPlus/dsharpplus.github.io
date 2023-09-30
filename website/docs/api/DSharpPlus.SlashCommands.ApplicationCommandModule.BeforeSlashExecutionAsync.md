# Method BeforeSlashExecutionAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_ApplicationCommandModule_BeforeSlashExecutionAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>BeforeSlashExecutionAsync\(InteractionContext\)

Called before the execution of a slash command in the module.

```csharp
public virtual Task<bool> BeforeSlashExecutionAsync(InteractionContext ctx)
```

### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

The context.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether or not to execute the slash command.

