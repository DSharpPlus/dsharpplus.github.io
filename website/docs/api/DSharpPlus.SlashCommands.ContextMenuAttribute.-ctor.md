# Constructor ContextMenuAttribute

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_ContextMenuAttribute__ctor_DSharpPlus_ApplicationCommandType_System_String_System_Boolean_System_Boolean_"></a>ContextMenuAttribute\(ApplicationCommandType, string, bool, bool\)

Marks this method as a context menu.

```csharp
public ContextMenuAttribute(ApplicationCommandType type, string name, bool defaultPermission = true, bool nsfw = false)
```

### Parameters

`type` [ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

The type of the context menu.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the context menu.

`defaultPermission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command should be enabled by default.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets whether the command is age restricted.

