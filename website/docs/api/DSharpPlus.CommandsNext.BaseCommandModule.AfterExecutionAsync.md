# Method AfterExecutionAsync

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_BaseCommandModule_AfterExecutionAsync_DSharpPlus_CommandsNext_CommandContext_"></a>AfterExecutionAsync\(CommandContext\)

Called after a command in the implementing module is successfully executed.

```csharp
public virtual Task AfterExecutionAsync(CommandContext ctx)
```

### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the method is being executed.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

