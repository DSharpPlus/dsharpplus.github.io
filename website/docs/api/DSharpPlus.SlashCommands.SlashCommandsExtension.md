# Class SlashCommandsExtension

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

A class that handles slash commands for a client.

```csharp
public sealed class SlashCommandsExtension : BaseExtension
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseExtension](DSharpPlus.BaseExtension.md) ← 
[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)

###### Inherited Members

[BaseExtension.Client](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Client), 
[BaseExtension.Dispose\(\)](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Dispose)

## Properties

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RegisteredCommands"></a>RegisteredCommands

Gets a list of registered commands. The key is the guild id (null if global).

```csharp
public IReadOnlyList<KeyValuePair<ulong?, IReadOnlyList<DiscordApplicationCommand>>> RegisteredCommands { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[KeyValuePair](https://learn.microsoft.com/dotnet/api/system.collections.generic.keyvaluepair\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?, [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>\>

## Methods

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_Dispose"></a>Dispose\(\)

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

```csharp
public override void Dispose()
```

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RefreshCommands"></a>RefreshCommands\(\)

<p>Refreshes your commands, used for refreshing choice providers or applying commands registered after the ready event on the discord client.
Should only be run on the slash command extension linked to shard 0 if sharding.</p>
<p>Not recommended and should be avoided since it can make slash commands be unresponsive for a while.</p>

```csharp
public Task RefreshCommands()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RegisterCommands__1_System_Nullable_System_UInt64__"></a>RegisterCommands<T\>\(ulong?\)

Registers a command class.

```csharp
public void RegisterCommands<T>(ulong? guildId = null) where T : ApplicationCommandModule
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

#### Type Parameters

`T` 

The command class to register.

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RegisterCommands_System_Type_System_Nullable_System_UInt64__"></a>RegisterCommands\(Type, ulong?\)

Registers a command class.

```csharp
public void RegisterCommands(Type type, ulong? guildId = null)
```

#### Parameters

`type` [Type](https://learn.microsoft.com/dotnet/api/system.type)

The <xref href="System.Type" data-throw-if-not-resolved="false"></xref> of the command class to register.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_RegisterCommands_System_Reflection_Assembly_System_Nullable_System_UInt64__"></a>RegisterCommands\(Assembly, ulong?\)

Registers all command classes from a given assembly.

```csharp
public void RegisterCommands(Assembly assembly, ulong? guildId = null)
```

#### Parameters

`assembly` [Assembly](https://learn.microsoft.com/dotnet/api/system.reflection.assembly)

Assembly to register command classes from.

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The guild id to register it on. If you want global commands, leave it null.

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_Setup_DSharpPlus_DiscordClient_"></a>Setup\(DiscordClient\)

Runs setup. DO NOT RUN THIS MANUALLY. DO NOT DO ANYTHING WITH THIS.

```csharp
protected override void Setup(DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

The client to setup on.

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_AutocompleteErrored"></a>AutocompleteErrored

```csharp
public event AsyncEventHandler<SlashCommandsExtension, AutocompleteErrorEventArgs> AutocompleteErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [AutocompleteErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.AutocompleteErrorEventArgs.md)\>

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_AutocompleteExecuted"></a>AutocompleteExecuted

```csharp
public event AsyncEventHandler<SlashCommandsExtension, AutocompleteExecutedEventArgs> AutocompleteExecuted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [AutocompleteExecutedEventArgs](DSharpPlus.SlashCommands.EventArgs.AutocompleteExecutedEventArgs.md)\>

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_ContextMenuErrored"></a>ContextMenuErrored

Fires when the execution of a context menu fails.

```csharp
public event AsyncEventHandler<SlashCommandsExtension, ContextMenuErrorEventArgs> ContextMenuErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [ContextMenuErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuErrorEventArgs.md)\>

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_ContextMenuExecuted"></a>ContextMenuExecuted

Fire when the execution of a context menu is successful.

```csharp
public event AsyncEventHandler<SlashCommandsExtension, ContextMenuExecutedEventArgs> ContextMenuExecuted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [ContextMenuExecutedEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuExecutedEventArgs.md)\>

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_ContextMenuInvoked"></a>ContextMenuInvoked

Fired when a context menu has been received and is to be executed

```csharp
public event AsyncEventHandler<SlashCommandsExtension, ContextMenuInvokedEventArgs> ContextMenuInvoked
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [ContextMenuInvokedEventArgs](DSharpPlus.SlashCommands.EventArgs.ContextMenuInvokedEventArgs.md)\>

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_SlashCommandErrored"></a>SlashCommandErrored

Fires when the execution of a slash command fails.

```csharp
public event AsyncEventHandler<SlashCommandsExtension, SlashCommandErrorEventArgs> SlashCommandErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [SlashCommandErrorEventArgs](DSharpPlus.SlashCommands.EventArgs.SlashCommandErrorEventArgs.md)\>

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_SlashCommandExecuted"></a>SlashCommandExecuted

Fires when the execution of a slash command is successful.

```csharp
public event AsyncEventHandler<SlashCommandsExtension, SlashCommandExecutedEventArgs> SlashCommandExecuted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [SlashCommandExecutedEventArgs](DSharpPlus.SlashCommands.EventArgs.SlashCommandExecutedEventArgs.md)\>

### <a id="DSharpPlus_SlashCommands_SlashCommandsExtension_SlashCommandInvoked"></a>SlashCommandInvoked

Fired when a slash command has been received and is to be executed

```csharp
public event AsyncEventHandler<SlashCommandsExtension, SlashCommandInvokedEventArgs> SlashCommandInvoked
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md), [SlashCommandInvokedEventArgs](DSharpPlus.SlashCommands.EventArgs.SlashCommandInvokedEventArgs.md)\>

