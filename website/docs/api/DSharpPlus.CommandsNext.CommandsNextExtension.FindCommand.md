# Method FindCommand

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextExtension_FindCommand_System_String_System_String__"></a>FindCommand\(string, out string?\)

Finds a specified command by its qualified name, then separates arguments.

```csharp
public Command? FindCommand(string commandString, out string? rawArguments)
```

### Parameters

`commandString` [string](https://learn.microsoft.com/dotnet/api/system.string)

Qualified name of the command, optionally with arguments.

`rawArguments` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Separated arguments.

### Returns

[Command](DSharpPlus.CommandsNext.Command.md)?

Found command or null if none was found.

