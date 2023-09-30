# Class ExtensionMethods

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Defines various extension methods for slash commands.

```csharp
public static class ExtensionMethods
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ExtensionMethods](DSharpPlus.SlashCommands.ExtensionMethods.md)

## Methods

### <a id="DSharpPlus_SlashCommands_ExtensionMethods_GetName__1___0_"></a>GetName<T\>\(T\)

Gets the name from the <xref href="DSharpPlus.SlashCommands.ChoiceNameAttribute" data-throw-if-not-resolved="false"></xref> for this enum value.

```csharp
public static string GetName<T>(this T e) where T : IConvertible
```

#### Parameters

`e` T

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The name.

#### Type Parameters

`T` 

### <a id="DSharpPlus_SlashCommands_ExtensionMethods_GetSlashCommands_DSharpPlus_DiscordClient_"></a>GetSlashCommands\(DiscordClient\)

Gets the slash commands module for this client.

```csharp
public static SlashCommandsExtension GetSlashCommands(this DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Client to get slash commands for.

#### Returns

[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)

The module, or null if not activated.

### <a id="DSharpPlus_SlashCommands_ExtensionMethods_RegisterCommands__1_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_SlashCommands_SlashCommandsExtension__System_Nullable_System_UInt64__"></a>RegisterCommands<T\>\(IReadOnlyDictionary<int, SlashCommandsExtension\>, ulong?\)

Registers a commands class.

```csharp
public static void RegisterCommands<T>(this IReadOnlyDictionary<int, SlashCommandsExtension> modules, ulong? guildId = null) where T : ApplicationCommandModule
```

#### Parameters

`modules` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)\>

The modules to register it on.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

#### Type Parameters

`T` 

The command class to register.

### <a id="DSharpPlus_SlashCommands_ExtensionMethods_RegisterCommands_System_Collections_Generic_IReadOnlyDictionary_System_Int32_DSharpPlus_SlashCommands_SlashCommandsExtension__System_Type_System_Nullable_System_UInt64__"></a>RegisterCommands\(IReadOnlyDictionary<int, SlashCommandsExtension\>, Type, ulong?\)

Registers a command class.

```csharp
public static void RegisterCommands(this IReadOnlyDictionary<int, SlashCommandsExtension> modules, Type type, ulong? guildId = null)
```

#### Parameters

`modules` [IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)\>

The modules to register it on.

`type` [Type](https://learn.microsoft.com/dotnet/api/system.type)

The <xref href="System.Type" data-throw-if-not-resolved="false"></xref> of the command class to register.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

### <a id="DSharpPlus_SlashCommands_ExtensionMethods_UseSlashCommands_DSharpPlus_DiscordClient_DSharpPlus_SlashCommands_SlashCommandsConfiguration_"></a>UseSlashCommands\(DiscordClient, SlashCommandsConfiguration\)

Enables slash commands on this <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static SlashCommandsExtension UseSlashCommands(this DiscordClient client, SlashCommandsConfiguration config = null)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

Client to enable slash commands for.

`config` [SlashCommandsConfiguration](DSharpPlus.SlashCommands.SlashCommandsConfiguration.md)

Configuration to use.

#### Returns

[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)

Created <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_SlashCommands_ExtensionMethods_UseSlashCommandsAsync_DSharpPlus_DiscordShardedClient_DSharpPlus_SlashCommands_SlashCommandsConfiguration_"></a>UseSlashCommandsAsync\(DiscordShardedClient, SlashCommandsConfiguration\)

Enables slash commands on this <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

```csharp
public static Task<IReadOnlyDictionary<int, SlashCommandsExtension>> UseSlashCommandsAsync(this DiscordShardedClient client, SlashCommandsConfiguration config = null)
```

#### Parameters

`client` [DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

Client to enable slash commands on.

`config` [SlashCommandsConfiguration](DSharpPlus.SlashCommands.SlashCommandsConfiguration.md)

Configuration to use.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)\>\>

A dictionary of created <xref href="DSharpPlus.SlashCommands.SlashCommandsExtension" data-throw-if-not-resolved="false"></xref> with the key being the shard id.

