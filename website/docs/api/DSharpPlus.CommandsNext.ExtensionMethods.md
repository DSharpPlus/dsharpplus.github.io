# Class ExtensionMethods

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

Defines various extensions specific to CommandsNext.

```csharp
public static class ExtensionMethods
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ExtensionMethods](DSharpPlus.CommandsNext.ExtensionMethods.md)

## Methods

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_GetCommandsNext_DSharpPlus_DiscordClient_"></a>GetCommandsNext\(DiscordClient\)

Gets the active CommandsNext module for this client.

```csharp
public static CommandsNextExtension GetCommandsNext(this DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Client to get CommandsNext module from.

#### Returns

[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)

The module, or null if not activated.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_GetCommandsNextAsync_DSharpPlus_DiscordShardedClient_"></a>GetCommandsNextAsync\(DiscordShardedClient\)

Gets the active CommandsNext modules for all shards in this client.

```csharp
public static Task<IReadOnlyDictionary<int, CommandsNextExtension>> GetCommandsNextAsync(this DiscordShardedClient client)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Client to get CommandsNext instances from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>\>

A dictionary of the modules, indexed by shard id.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__System_Reflection_Assembly_"></a>RegisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, Assembly\)

Registers all commands from a given assembly. The command classes need to be public to be considered for registration.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, Assembly assembly)
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

`assembly` [Assembly](https://learn.microsoft.com/dotnet/api/system.reflection.assembly)

Assembly to register commands from.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__"></a>RegisterCommands<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>\)

Registers all commands from a given command class.

```csharp
public static void RegisterCommands<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions) where T : BaseCommandModule
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

#### Type Parameters

`T` 

Class which holds commands to register.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__System_Type_"></a>RegisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, Type\)

Registers all commands from a given command class.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, Type t)
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

`t` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type of the class which holds commands to register.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__DSharpPlus_CommandsNext_Builders_CommandBuilder___"></a>RegisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, params CommandBuilder\[\]\)

Builds and registers all supplied commands.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, params CommandBuilder[] cmds)
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register commands on.

`cmds` [CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)\[\]

Commands to build and register.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterConverter__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__DSharpPlus_CommandsNext_Converters_IArgumentConverter___0__"></a>RegisterConverter<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>, IArgumentConverter<T\>\)

Registers an argument converter for specified type.

```csharp
public static void RegisterConverter<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, IArgumentConverter<T> converter)
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register the converter on.

`converter` [IArgumentConverter](DSharpPlus.CommandsNext.Converters.IArgumentConverter\-1.md)<T\>

Converter to register.

#### Type Parameters

`T` 

Type for which to register the converter.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_RegisterUserFriendlyTypeName__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__System_String_"></a>RegisterUserFriendlyTypeName<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>, string\)

Registers a user-friendly type name.

```csharp
public static void RegisterUserFriendlyTypeName<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, string value)
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to register the name on.

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name to register.

#### Type Parameters

`T` 

Type to register the name for.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_SetHelpFormatter__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__"></a>SetHelpFormatter<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>\)

Sets the help formatter to use with the default help command.

```csharp
public static void SetHelpFormatter<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions) where T : BaseHelpFormatter
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to set the help formatter on.

#### Type Parameters

`T` 

Type of the formatter to use.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_UnregisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__DSharpPlus_CommandsNext_Command___"></a>UnregisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, params Command\[\]\)

Unregisters specified commands from CommandsNext.

```csharp
public static void UnregisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, params Command[] cmds)
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to unregister commands on.

`cmds` [Command](DSharpPlus.CommandsNext.Command.md)\[\]

Commands to unregister.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_UnregisterConverter__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__"></a>UnregisterConverter<T\>\(IReadOnlyDictionary<int, CommandsNextExtension\>\)

Unregisters an argument converter for specified type.

```csharp
public static void UnregisterConverter<T>(this IReadOnlyDictionary<int, CommandsNextExtension> extensions)
```

#### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to unregister the converter on.

#### Type Parameters

`T` 

Type for which to unregister the converter.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_UseCommandsNext_DSharpPlus_DiscordClient_DSharpPlus_CommandsNext_CommandsNextConfiguration_"></a>UseCommandsNext\(DiscordClient, CommandsNextConfiguration\)

Enables CommandsNext module on this <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static CommandsNextExtension UseCommandsNext(this DiscordClient client, CommandsNextConfiguration cfg)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Client to enable CommandsNext for.

`cfg` [CommandsNextConfiguration](DSharpPlus.CommandsNext.CommandsNextConfiguration.md)

CommandsNext configuration to use.

#### Returns

[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)

Created <xref href="DSharpPlus.CommandsNext.CommandsNextExtension" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_CommandsNext_ExtensionMethods_UseCommandsNextAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_CommandsNext_CommandsNextConfiguration_"></a>UseCommandsNextAsync\(DiscordShardedClient, CommandsNextConfiguration\)

Enables CommandsNext module on all shards in this <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static Task<IReadOnlyDictionary<int, CommandsNextExtension>> UseCommandsNextAsync(this DiscordShardedClient client, CommandsNextConfiguration cfg)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Client to enable CommandsNext for.

`cfg` [CommandsNextConfiguration](DSharpPlus.CommandsNext.CommandsNextConfiguration.md)

CommandsNext configuration to use.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>\>

A dictionary of created <xref href="DSharpPlus.CommandsNext.CommandsNextExtension" data-throw-if-not-resolved="false"></xref>, indexed by shard id.

