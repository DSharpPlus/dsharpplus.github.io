# Method ExecuteChecksAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_SlashCheckBaseAttribute_ExecuteChecksAsync_DSharpPlus_SlashCommands_InteractionContext_"></a>ExecuteChecksAsync\(InteractionContext\)

Checks whether this command can be executed within the current context.

```csharp
public abstract Task<bool> ExecuteChecksAsync(InteractionContext ctx)
```

### Parameters

`ctx` [InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

The context.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the checks passed.

