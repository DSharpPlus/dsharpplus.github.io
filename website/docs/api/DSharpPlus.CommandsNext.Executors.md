# Namespace DSharpPlus.CommandsNext.Executors

### Classes

[AsynchronousCommandExecutor](DSharpPlus.CommandsNext.Executors.AsynchronousCommandExecutor.md)

Executes commands using <xref href="System.Threading.Tasks.Task.Run(System.Func%7bSystem.Threading.Tasks.Task%7d)" data-throw-if-not-resolved="false"></xref>.

[ParallelQueuedCommandExecutor](DSharpPlus.CommandsNext.Executors.ParallelQueuedCommandExecutor.md)

A command executor which uses a bounded pool of executors to execute commands. This can limit the impact of
commands on system resources, such as CPU usage.

[SynchronousCommandExecutor](DSharpPlus.CommandsNext.Executors.SynchronousCommandExecutor.md)

Executes commands by awaiting them.

### Interfaces

[ICommandExecutor](DSharpPlus.CommandsNext.Executors.ICommandExecutor.md)

Defines an API surface for all command executors.

