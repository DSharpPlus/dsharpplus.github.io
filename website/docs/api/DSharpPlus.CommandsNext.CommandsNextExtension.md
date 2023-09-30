# Class CommandsNextExtension

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

This is the class which handles command registration, management, and execution.

```csharp
public class CommandsNextExtension : BaseExtension
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseExtension](DSharpPlus.BaseExtension.md) ← 
[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md)

###### Inherited Members

[BaseExtension.Client](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Client), 
[BaseExtension.Dispose\(\)](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Dispose), 
[BaseExtension.Setup\(DiscordClient\)](DSharpPlus.BaseExtension.md\#DSharpPlus\_BaseExtension\_Setup\_DSharpPlus\_DiscordClient\_)

## Properties

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisteredCommands"></a>RegisteredCommands

Gets a dictionary of registered top-level commands.

```csharp
public IReadOnlyDictionary<string, Command> RegisteredCommands { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [Command](DSharpPlus.CommandsNext.Command.md)\>

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_Services"></a>Services

Gets the service provider this CommandsNext module was configured with.

```csharp
public IServiceProvider Services { get; }
```

#### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

## Methods

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_ConvertArgument__1_System_String_DSharpPlus_CommandsNext_CommandContext_"></a>ConvertArgument<T\>\(string, CommandContext\)

Converts a string to specified type.

```csharp
public Task<object> ConvertArgument<T>(string value, CommandContext ctx)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Value to convert.

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which to convert to.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[object](https://learn.microsoft.com/dotnet/api/system.object)\>

Converted object.

#### Type Parameters

`T` 

Type to convert to.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_ConvertArgument_System_String_DSharpPlus_CommandsNext_CommandContext_System_Type_"></a>ConvertArgument\(string?, CommandContext, Type\)

Converts a string to specified type.

```csharp
public Task<object> ConvertArgument(string? value, CommandContext ctx, Type type)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Value to convert.

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context in which to convert to.

`type` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type to convert to.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[object](https://learn.microsoft.com/dotnet/api/system.object)\>

Converted object.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_CreateContext_DSharpPlus_Entities_DiscordMessage_System_String_DSharpPlus_CommandsNext_Command_System_String_"></a>CreateContext\(DiscordMessage, string, Command?, string?\)

Creates a command execution context from specified arguments.

```csharp
public CommandContext CreateContext(DiscordMessage msg, string prefix, Command? cmd, string? rawArguments = null)
```

#### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to use for context.

`prefix` [string](https://learn.microsoft.com/dotnet/api/system.string)

Command prefix, used to execute commands.

`cmd` [Command](DSharpPlus.CommandsNext.Command.md)?

Command to execute.

`rawArguments` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Raw arguments to pass to command.

#### Returns

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Created command execution context.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_CreateFakeContext_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordChannel_System_String_System_String_DSharpPlus_CommandsNext_Command_System_String_"></a>CreateFakeContext\(DiscordUser, DiscordChannel, string, string, Command, string?\)

Creates a fake command context to execute commands with.

```csharp
public CommandContext CreateFakeContext(DiscordUser actor, DiscordChannel channel, string messageContents, string prefix, Command cmd, string? rawArguments = null)
```

#### Parameters

`actor` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user or member to use as message author.

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel the message is supposed to appear from.

`messageContents` [string](https://learn.microsoft.com/dotnet/api/system.string)

Contents of the message.

`prefix` [string](https://learn.microsoft.com/dotnet/api/system.string)

Command prefix, used to execute commands.

`cmd` [Command](DSharpPlus.CommandsNext.Command.md)

Command to execute.

`rawArguments` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Raw arguments to pass to command.

#### Returns

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Created fake context.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_Dispose"></a>Dispose\(\)

Disposes of this the resources used by CNext.

```csharp
public override void Dispose()
```

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_ExecuteCommandAsync_DSharpPlus_CommandsNext_CommandContext_"></a>ExecuteCommandAsync\(CommandContext\)

Executes specified command from given context.

```csharp
public Task ExecuteCommandAsync(CommandContext ctx)
```

#### Parameters

`ctx` [CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Context to execute command from.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_FindCommand_System_String_System_String__"></a>FindCommand\(string, out string?\)

Finds a specified command by its qualified name, then separates arguments.

```csharp
public Command? FindCommand(string commandString, out string? rawArguments)
```

#### Parameters

`commandString` [string](https://learn.microsoft.com/dotnet/api/system.string)

Qualified name of the command, optionally with arguments.

`rawArguments` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Separated arguments.

#### Returns

[Command](DSharpPlus.CommandsNext.Command.md)?

Found command or null if none was found.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_GetUserFriendlyTypeName_System_Type_"></a>GetUserFriendlyTypeName\(Type\)

Converts a type into user-friendly type name.

```csharp
public string GetUserFriendlyTypeName(Type t)
```

#### Parameters

`t` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type to convert.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

User-friendly type name.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands_System_Reflection_Assembly_"></a>RegisterCommands\(Assembly\)

Registers all commands from a given assembly. The command classes need to be public to be considered for registration.

```csharp
public void RegisterCommands(Assembly assembly)
```

#### Parameters

`assembly` [Assembly](https://learn.microsoft.com/dotnet/api/system.reflection.assembly)

Assembly to register commands from.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands__1"></a>RegisterCommands<T\>\(\)

Registers all commands from a given command class.

```csharp
public void RegisterCommands<T>() where T : BaseCommandModule
```

#### Type Parameters

`T` 

Class which holds commands to register.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands_System_Type_"></a>RegisterCommands\(Type\)

Registers all commands from a given command class.

```csharp
public void RegisterCommands(Type t)
```

#### Parameters

`t` [Type](https://learn.microsoft.com/dotnet/api/system.type)

Type of the class which holds commands to register.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterCommands_DSharpPlus_CommandsNext_Builders_CommandBuilder___"></a>RegisterCommands\(params CommandBuilder\[\]\)

Builds and registers all supplied commands.

```csharp
public void RegisterCommands(params CommandBuilder[] cmds)
```

#### Parameters

`cmds` [CommandBuilder](DSharpPlus.CommandsNext.Builders.CommandBuilder.md)\[\]

Commands to build and register.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterConverter__1_DSharpPlus_CommandsNext_Converters_IArgumentConverter___0__"></a>RegisterConverter<T\>\(IArgumentConverter<T\>\)

Registers an argument converter for specified type.

```csharp
public void RegisterConverter<T>(IArgumentConverter<T> converter)
```

#### Parameters

`converter` [IArgumentConverter](DSharpPlus.CommandsNext.Converters.IArgumentConverter\-1.md)<T\>

Converter to register.

#### Type Parameters

`T` 

Type for which to register the converter.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_RegisterUserFriendlyTypeName__1_System_String_"></a>RegisterUserFriendlyTypeName<T\>\(string\)

Registers a user-friendly type name.

```csharp
public void RegisterUserFriendlyTypeName<T>(string value)
```

#### Parameters

`value` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name to register.

#### Type Parameters

`T` 

Type to register the name for.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_SetHelpFormatter__1"></a>SetHelpFormatter<T\>\(\)

Sets the help formatter to use with the default help command.

```csharp
public void SetHelpFormatter<T>() where T : BaseHelpFormatter
```

#### Type Parameters

`T` 

Type of the formatter to use.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_Setup_DSharpPlus_DiscordClient_"></a>Setup\(DiscordClient\)

DO NOT USE THIS MANUALLY.

```csharp
protected override void Setup(DiscordClient client)
```

#### Parameters

`client` [DiscordClient](DSharpPlus.DiscordClient.md)

DO NOT USE THIS MANUALLY.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_UnregisterCommands_DSharpPlus_CommandsNext_Command___"></a>UnregisterCommands\(params Command\[\]\)

Unregisters specified commands from CommandsNext.

```csharp
public void UnregisterCommands(params Command[] cmds)
```

#### Parameters

`cmds` [Command](DSharpPlus.CommandsNext.Command.md)\[\]

Commands to unregister.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_UnregisterConverter__1"></a>UnregisterConverter<T\>\(\)

Unregisters an argument converter for specified type.

```csharp
public void UnregisterConverter<T>()
```

#### Type Parameters

`T` 

Type for which to unregister the converter.

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_CommandErrored"></a>CommandErrored

Triggered whenever a command throws an exception during execution.

```csharp
public event AsyncEventHandler<CommandsNextExtension, CommandErrorEventArgs> CommandErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md), [CommandErrorEventArgs](DSharpPlus.CommandsNext.CommandErrorEventArgs.md)\>

### <a id="DSharpPlus_CommandsNext_CommandsNextExtension_CommandExecuted"></a>CommandExecuted

Triggered whenever a command executes successfully.

```csharp
public event AsyncEventHandler<CommandsNextExtension, CommandExecutionEventArgs> CommandExecuted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[CommandsNextExtension](DSharpPlus.CommandsNext.CommandsNextExtension.md), [CommandExecutionEventArgs](DSharpPlus.CommandsNext.CommandExecutionEventArgs.md)\>

