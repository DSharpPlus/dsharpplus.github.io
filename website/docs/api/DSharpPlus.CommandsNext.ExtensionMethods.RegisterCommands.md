# Method RegisterCommands

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__System_Reflection_Assembly_"></a>RegisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, Assembly\)

Registers all commands from a given assembly. The command classes need to be public to be considered for registration.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, Assembly assembly)
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

`assembly` [Assembly](https://learn.microsoft.com/dotnet/api/system.reflection.assembly)

Assembly to register commands from.

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__"></a>RegisterCommands<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>\)

Registers all commands from a given command class.

```csharp
public static void RegisterCommands<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions) where T : BaseCommandModule
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

### Type Parameters

`T` 

Class which holds commands to register.

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__System_Type_"></a>RegisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, Type\)

Registers all commands from a given command class.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, Type t)
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

`t` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type of the class which holds commands to register.

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__DSharpPlus_CommandsNext_Builders_CommandBuilder___"></a>RegisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, params CommandBuilder\[\]\)

Builds and registers all supplied commands.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, params CommandBuilder[] cmds)
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

`cmds` [CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)\[\]

Commands to build and register.

