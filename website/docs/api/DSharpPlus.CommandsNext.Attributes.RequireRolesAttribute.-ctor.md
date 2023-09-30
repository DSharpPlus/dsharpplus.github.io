# Constructor RequireRolesAttribute

Namespace: [DSharpPlus.CommandsNext.Attributes](DSharpPlus.CommandsNext.Attributes.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute__ctor_DSharpPlus_CommandsNext_Attributes_RoleCheckMode_System_String___"></a>RequireRolesAttribute\(RoleCheckMode, params string\[\]\)

Defines that usage of this command is restricted to members with specified role. Note that it's much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

```csharp
public RequireRolesAttribute(RoleCheckMode checkMode, params string[] roleNames)
```

### Parameters

`checkMode` [RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

Role checking mode.

`roleNames` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

Names of the role to be verified by this check.

## <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute__ctor_DSharpPlus_CommandsNext_Attributes_RoleCheckMode_System_UInt64___"></a>RequireRolesAttribute\(RoleCheckMode, params ulong\[\]\)

Defines that usage of this command is restricted to members with the specified role.
Note that it is much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

```csharp
public RequireRolesAttribute(RoleCheckMode checkMode, params ulong[] roleIds)
```

### Parameters

`checkMode` [RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

Role checking mode.

`roleIds` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\[\]

IDs of the roles to be verified by this check.

## <a id="DSharpPlus_CommandsNext_Attributes_RequireRolesAttribute__ctor_DSharpPlus_CommandsNext_Attributes_RoleCheckMode_System_String___System_UInt64___"></a>RequireRolesAttribute\(RoleCheckMode, string\[\], ulong\[\]\)

Defines that usage of this command is restricted to members with the specified role.
Note that it is much preferred to restrict access using <xref href="DSharpPlus.CommandsNext.Attributes.RequirePermissionsAttribute" data-throw-if-not-resolved="false"></xref>.

```csharp
public RequireRolesAttribute(RoleCheckMode checkMode, string[] roleNames, ulong[] roleIds)
```

### Parameters

`checkMode` [RoleCheckMode](DSharpPlus.CommandsNext.Attributes.RoleCheckMode.md)

Role checking mode.

`roleNames` [string](https://learn.microsoft.com/dotnet/api/system.string)\[\]

Names of the role to be verified by this check.

`roleIds` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\[\]

IDs of the roles to be verified by this check.

