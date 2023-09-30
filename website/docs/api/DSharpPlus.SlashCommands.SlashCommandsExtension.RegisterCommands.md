# Method RegisterCommands<T\>

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RegisterCommands__1_System_Nullable_System_UInt64__"></a>RegisterCommands<T\>\(ulong?\)

Registers a command class.

```csharp
public void RegisterCommands<T>(ulong? guildId = null) where T : ApplicationCommandModule
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

### Type Parameters

`T` 

The command class to register.

## <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RegisterCommands_System_Type_System_Nullable_System_UInt64__"></a>RegisterCommands\(Type, ulong?\)

Registers a command class.

```csharp
public void RegisterCommands(Type type, ulong? guildId = null)
```

### Parameters

`type` [Type](https://learn.microsoft.com/dotnet/api/system.type)

The <xref href="System.Type" data-throw-if-not-resolved="false"></xref> of the command class to register.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

## <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RegisterCommands_System_Reflection_Assembly_System_Nullable_System_UInt64__"></a>RegisterCommands\(Assembly, ulong?\)

Registers all command classes from a given assembly.

```csharp
public void RegisterCommands(Assembly assembly, ulong? guildId = null)
```

### Parameters

`assembly` [Assembly](https://learn.microsoft.com/dotnet/api/system.reflection.assembly)

Assembly to register command classes from.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

