# Method UnregisterCommands

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_ExtensionMethods_UnregisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_CommandsNext_CommandsNextExtension__DSharpPlus_CommandsNext_Command___"></a>UnregisterCommands\(IReadOnlyDictionary<int, CommandsNextExtension\>, params Command\[\]\)

Unregisters specified commands from CommandsNext.

```csharp
public static void UnregisterCommands(this IReadOnlyDictionary<int, CommandsNextExtension> extensions, params Command[] cmds)
```

### Parameters

`extensions` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)\>

Extensions to unregister commands on.

`cmds` [Command](DSharpPlus.CommandsNext.Command.md)\[\]

Commands to unregister.

