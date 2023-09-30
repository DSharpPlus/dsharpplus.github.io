# Interface ICommandExecutor

Namespace: [DSharpPlus.CommandsNext.Executors](DSharpPlus.CommandsNext.Executors.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines an API surface for all command executors.

```csharp
public interface ICommandExecutor
```

## Methods

### <a id="DSharpPlus_CommandsNext_Executors_ICommandExecutor_ExecuteAsync_DSharpPlus_CommandsNext_CommandContext_"></a>ExecuteAsync\(CommandContext\)

Executes a command from given context.

```csharp
Task ExecuteAsync(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context to execute in.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Task encapsulating the async operation.

