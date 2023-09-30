# Constructor ParallelQueuedCommandExecutor

Namespace: [DSharpPlus.CommandsNext.Executors](DSharpPlus.CommandsNext.Executors.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Executors_ParallelQueuedCommandExecutor__ctor"></a>ParallelQueuedCommandExecutor\(\)

Creates a new executor, which uses up to 75% of system CPU resources.

```csharp
public ParallelQueuedCommandExecutor()
```

## <a id="DSharpPlus_CommandsNext_Executors_ParallelQueuedCommandExecutor__ctor_System_Int32_"></a>ParallelQueuedCommandExecutor\(int\)

Creates a new executor with specified degree of parallelism.

```csharp
public ParallelQueuedCommandExecutor(int parallelism)
```

### Parameters

`parallelism` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The number of workers to use. It is recommended this number does not exceed 150% of the physical CPU count.

