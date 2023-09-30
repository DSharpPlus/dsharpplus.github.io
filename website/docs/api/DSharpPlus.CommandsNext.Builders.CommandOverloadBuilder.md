# Class CommandOverloadBuilder

Namespace: [DSharpPlus.CommandsNext.Builders](DSharpPlus.CommandsNext.Builders.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents an interface to build a command overload.

```csharp
public sealed class CommandOverloadBuilder
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[CommandOverloadBuilder](DSharpPlus.CommandsNext.Builders.CommandOverloadBuilder.md)

## Constructors

### <a id="DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder__ctor_System_Reflection_MethodInfo_"></a>CommandOverloadBuilder\(MethodInfo\)

Creates a new command overload builder from specified method.

```csharp
public CommandOverloadBuilder(MethodInfo method)
```

#### Parameters

`method` [MethodInfo](https://learn.microsoft.com/dotnet/api/system.reflection.methodinfo)

Method to use for this overload.

### <a id="DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder__ctor_System_Delegate_"></a>CommandOverloadBuilder\(Delegate\)

Creates a new command overload builder from specified delegate.

```csharp
public CommandOverloadBuilder(Delegate method)
```

#### Parameters

`method` [Delegate](https://learn.microsoft.com/dotnet/api/system.delegate)

Delegate to use for this overload.

## Properties

### <a id="DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder_Arguments"></a>Arguments

Gets the collection of arguments this overload takes.

```csharp
public IReadOnlyList<CommandArgument> Arguments { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[CommandArgument](DSharpPlus.CommandsNext.CommandArgument.md)\>

### <a id="DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder_Callable"></a>Callable

Gets the overload's callable delegate.

```csharp
public Delegate Callable { get; set; }
```

#### Property Value

[Delegate](https://learn.microsoft.com/dotnet/api/system.delegate)

### <a id="DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder_Priority"></a>Priority

Gets this overload's priority when picking a suitable one for execution.

```csharp
public int Priority { get; set; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_CommandsNext_Builders_CommandOverloadBuilder_WithPriority_System_Int32_"></a>WithPriority\(int\)

Sets the priority for this command overload.

```csharp
public CommandOverloadBuilder WithPriority(int priority)
```

#### Parameters

`priority` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Priority for this command overload.

#### Returns

[CommandOverloadBuilder](DSharpPlus.CommandsNext.Builders.CommandOverloadBuilder.md)

This builder.

