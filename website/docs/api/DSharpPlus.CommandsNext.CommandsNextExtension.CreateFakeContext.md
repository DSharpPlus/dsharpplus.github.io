# Method CreateFakeContext

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_CreateFakeContext_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordChannel_System_String_System_String_DSharpPlus_CommandsNext_Command_System_String_"></a>CreateFakeContext\(DiscordUser, DiscordChannel, string, string, Command, string?\)

Creates a fake command context to execute commands with.

```csharp
public CommandContext CreateFakeContext(DiscordUser actor, DiscordChannel channel, string messageContents, string prefix, Command cmd, string? rawArguments = null)
```

### Parameters

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

### Returns

[CommandContext](DSharpPlus.CommandsNext.CommandContext.md)

Created fake context.

