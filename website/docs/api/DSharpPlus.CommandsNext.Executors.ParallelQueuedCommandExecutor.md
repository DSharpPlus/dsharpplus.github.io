# Class ParallelQueuedCommandExecutor

Namespace: [DSharpPlus.CommandsNext.Executors](DSharpPlus.CommandsNext.Executors.md)  
Assembly: DSharpPlus.CommandsNext.dll

A command executor which uses a bounded pool of executors to execute commands. This can limit the impact of
commands on system resources, such as CPU usage.

```csharp
public sealed class ParallelQueuedCommandExecutor : ICommandExecutor
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ParallelQueuedCommandExecutor](DSharpPlus.CommandsNext.Executors.ParallelQueuedCommandExecutor.md)

###### Implements

[ICommandExecutor](DSharpPlus.CommandsNext.Executors.ICommandExecutor.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Executors_ParallelQueuedCommandExecutor__ctor"></a>ParallelQueuedCommandExecutor\(\)

Creates a new executor, which uses up to 75% of system CPU resources.

```csharp
public ParallelQueuedCommandExecutor()
```

### <a id="DSharpPlus_CommandsNext_Executors_ParallelQueuedCommandExecutor__ctor_System_Int32_"></a>ParallelQueuedCommandExecutor\(int\)

Creates a new executor with specified degree of parallelism.

```csharp
public ParallelQueuedCommandExecutor(int parallelism)
```

#### Parameters

`parallelism` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The number of workers to use. It is recommended this number does not exceed 150% of the physical CPU count.

## Properties

### <a id="DSharpPlus_CommandsNext_Executors_ParallelQueuedCommandExecutor_Parallelism"></a>Parallelism

Gets the degree of parallelism of this executor.

```csharp
public int Parallelism { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_CommandsNext_Executors_ParallelQueuedCommandExecutor_Dispose"></a>Dispose\(\)

Disposes of the resources used by this executor.

```csharp
public void Dispose()
```

