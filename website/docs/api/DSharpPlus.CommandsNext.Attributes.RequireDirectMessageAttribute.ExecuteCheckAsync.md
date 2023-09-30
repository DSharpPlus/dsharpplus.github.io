# Method ExecuteCheckAsync

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Attributes_RequireDirectMessageAttribute_ExecuteCheckAsync_DSharpPlus_CommandsNext_CommandContext_System_Boolean_"></a>ExecuteCheckAsync\(CommandContext, bool\)

Asynchronously checks whether this command can be executed within given context.

```csharp
public override Task<bool> ExecuteCheckAsync(CommandContext ctx, bool help)
```

### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context to check execution ability for.

`help` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this check is being executed from help or not. This can be used to probe whether command can be run without setting off certain fail conditions (such as cooldowns).

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the command can be executed in given context.

