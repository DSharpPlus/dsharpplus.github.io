# Method RegisterCommands

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands_System_Reflection_Assembly_"></a>RegisterCommands\(Assembly\)

Registers all commands from a given assembly. The command classes need to be public to be considered for registration.

```csharp
public void RegisterCommands(Assembly assembly)
```

### Parameters

`assembly` [Assembly](https://learn.microsoft.com/dotnet/api/system.reflection.assembly)

Assembly to register commands from.

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands__1"></a>RegisterCommands<T\>\(\)

Registers all commands from a given command class.

```csharp
public void RegisterCommands<T>() where T : BaseCommandModule
```

### Type Parameters

`T` 

Class which holds commands to register.

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands_System_Type_"></a>RegisterCommands\(Type\)

Registers all commands from a given command class.

```csharp
public void RegisterCommands(Type t)
```

### Parameters

`t` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type of the class which holds commands to register.

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands_DSharpPlus_CommandsNext_Builders_CommandBuilder___"></a>RegisterCommands\(params CommandBuilder\[\]\)

Builds and registers all supplied commands.

```csharp
public void RegisterCommands(params CommandBuilder[] cmds)
```

### Parameters

`cmds` [CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)\[\]

Commands to build and register.

