# Constructor SlashCommandAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_SlashCommandAttribute__ctor_System_String_System_String_System_Boolean_System_Boolean_"></a>SlashCommandAttribute\(string, string, bool, bool\)

Marks this method as a slash command.

```csharp
public SlashCommandAttribute(string name, string description, bool defaultPermission = true, bool nsfw = false)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sets the name of this slash command.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Sets the description of this slash command.

`defaultPermission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command should be enabled by default.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command is age restricted.

