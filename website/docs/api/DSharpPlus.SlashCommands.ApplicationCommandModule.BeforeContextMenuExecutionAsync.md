# Method BeforeContextMenuExecutionAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_ApplicationCommandModule_BeforeContextMenuExecutionAsync_DSharpPlus_SlashCommands_ContextMenuContext_"></a>BeforeContextMenuExecutionAsync\(ContextMenuContext\)

Called before the execution of a context menu in the module.

```csharp
public virtual Task<bool> BeforeContextMenuExecutionAsync(ContextMenuContext ctx)
```

### Parameters

`ctx` [ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md)

The context.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether or not to execute the slash command.

