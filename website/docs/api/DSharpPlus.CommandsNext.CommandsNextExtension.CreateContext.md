# Method CreateContext

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_CreateContext_DSharpPlus_Entities_DiscordMessage_System_String_DSharpPlus_CommandsNext_Command_System_String_"></a>CreateContext\(DiscordMessage, string, Command?, string?\)

Creates a command execution context from specified arguments.

```csharp
public CommandContext CreateContext(DiscordMessage msg, string prefix, Command? cmd, string? rawArguments = null)
```

### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to use for context.

`prefix` [string](https://learn.microsoft.com/dotnet/api/system.string)

Command prefix, used to execute commands.

`cmd` [Command](DSharpPlus.CommandsNext.Command.md)?

Command to execute.

`rawArguments` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Raw arguments to pass to command.

### Returns

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Created command execution context.

