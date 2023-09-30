# Constructor SlashRequireUserPermissionsAttribute

Namespace: [DSharpPlus.SlashCommands.Attributes](DSharpPlus.SlashCommands.Attributes.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_Attributes_SlashRequireUserPermissionsAttribute__ctor_DSharpPlus_Permissions_System_Boolean_"></a>SlashRequireUserPermissionsAttribute\(Permissions, bool\)

Defines that usage of this command is restricted to members with specified permissions.

```csharp
public SlashRequireUserPermissionsAttribute(Permissions permissions, bool ignoreDms = true)
```

### Parameters

`permissions` [Permissions](DSharpPlus.Permissions.md)

Permissions required to execute this command.

`ignoreDms` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets this check's behaviour in DMs. True means the check will always pass in DMs, whereas false means that it will always fail.

