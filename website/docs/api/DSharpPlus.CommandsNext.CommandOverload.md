# Class CommandOverload

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a specific overload of a command.

```csharp
public sealed class CommandOverload
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandOverload](DSharpPlus.CommandsNext.CommandOverload.md)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandOverload_Arguments"></a>Arguments

Gets this command overload's arguments.

```csharp
public IReadOnlyList<CommandArgument> Arguments { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CommandArgument](DSharpPlus.CommandsNext.CommandArgument.md)\>

### <a id="DSharpPlus_CommandsNext_CommandOverload_Priority"></a>Priority

Gets this command overload's priority.

```csharp
public int Priority { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

