# Constructor RequireUserPermissionsAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Attributes_RequireUserPermissionsAttribute__ctor_DSharpPlus_Permissions_System_Boolean_"></a>RequireUserPermissionsAttribute\(Permissions, bool\)

Defines that usage of this command is restricted to members with specified permissions.

```csharp
public RequireUserPermissionsAttribute(Permissions permissions, bool ignoreDms = true)
```

### Parameters

`permissions` [Permissions](DSharpPlus.Permissions.md)

Permissions required to execute this command.

`ignoreDms` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Sets this check's behaviour in DMs. True means the check will always pass in DMs, whereas false means that it will always fail.
