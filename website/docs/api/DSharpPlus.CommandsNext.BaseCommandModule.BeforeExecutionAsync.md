# Method BeforeExecutionAsync

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_BaseCommandModule_BeforeExecutionAsync_DSharpPlus_CommandsNext_CommandContext_"></a>BeforeExecutionAsync\(CommandContext\)

Called before a command in the implementing module is executed.

```csharp
public virtual Task BeforeExecutionAsync(CommandContext ctx)
```

### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the method is being executed.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

