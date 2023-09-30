# Constructor SlashRequireBotPermissionsAttribute

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_Attributes_SlashRequireBotPermissionsAttribute__ctor_DSharpPlus_Permissions_System_Boolean_"></a>SlashRequireBotPermissionsAttribute\(Permissions, bool\)

Defines that usage of this slash command is only possible when the bot is granted a specific permission.

```csharp
public SlashRequireBotPermissionsAttribute(Permissions permissions, bool ignoreDms = true)
```

### Parameters

`permissions` [Permissions](DSharpPlus.Permissions.md)

Permissions required to execute this command.

`ignoreDms` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets this check's behaviour in DMs. True means the check will always pass in DMs, whereas false means that it will always fail.

