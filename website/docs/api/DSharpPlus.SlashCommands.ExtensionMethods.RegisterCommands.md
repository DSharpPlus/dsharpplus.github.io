# Method RegisterCommands<T\>

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_ExtensionMethods_RegisterCommands__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_SlashCommands_SlashCommandsExtension__System_Nullable_System_UInt64__"></a>RegisterCommands<T\>\(IReadOnlyDictionary<int, SlashCommandsExtension\>, ulong?\)

Registers a commands class.

```csharp
public static void RegisterCommands<T>(this IReadOnlyDictionary<int, SlashCommandsExtension> modules, ulong? guildId = null) where T : ApplicationCommandModule
```

### Parameters

`modules` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)\>

The modules to register it on.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

### Type Parameters

`T` 

The command class to register.

## <a id="DSharpPlus_SlashCommands_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_SlashCommands_SlashCommandsExtension__System_Type_System_Nullable_System_UInt64__"></a>RegisterCommands\(IReadOnlyDictionary<int, SlashCommandsExtension\>, Type, ulong?\)

Registers a command class.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, SlashCommandsExtension> modules, Type type, ulong? guildId = null)
```

### Parameters

`modules` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)\>

The modules to register it on.

`type` [Type](https://learn.microsoft.com/dotnet/api/system.type)

The <xref href="System.Type" data-throw-if-not-resolved="false"></xref> of the command class to register.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

