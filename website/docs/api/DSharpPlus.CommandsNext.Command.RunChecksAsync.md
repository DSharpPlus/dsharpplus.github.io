# Method RunChecksAsync

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Command_RunChecksAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>RunChecksAsync\(CommandContext, bool\)

Runs pre-execution checks for this command and returns any that fail for given context.

```csharp
public Task<IEnumerable<CheckBaseAttribute>> RunChecksAsync(CommandContext ctx, bool help)
```

### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which the command is executed.

`help` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this check is being executed from help or not. This can be used to probe whether command can be run without setting off certain fail conditions (such as cooldowns).

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[CheckBaseAttribute](DSharpPlus.CommandsNext.Attributes.CheckBaseAttribute.md)\>\>

Pre-execution checks that fail for given context.

