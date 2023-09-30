# Class PermissionMethods

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

```csharp
public static class PermissionMethods
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[PermissionMethods](DSharpPlus.PermissionMethods.md)

## Methods

### <a id="DSharpPlus_PermissionMethods_Grant_DSharpPlus_Permissions_DSharpPlus_Permissions_"></a>Grant\(Permissions, Permissions\)

Grants permissions.

```csharp
public static Permissions Grant(this Permissions p, Permissions grant)
```

#### Parameters

`p` [Permissions](DSharpPlus.Permissions.md)

The permissions to add to.

`grant` [Permissions](DSharpPlus.Permissions.md)

Permission to add.

#### Returns

[Permissions](DSharpPlus.Permissions.md)

### <a id="DSharpPlus_PermissionMethods_HasPermission_DSharpPlus_Permissions_DSharpPlus_Permissions_"></a>HasPermission\(Permissions, Permissions\)

Calculates whether this permission set contains the given permission.

```csharp
public static bool HasPermission(this Permissions p, Permissions permission)
```

#### Parameters

`p` [Permissions](DSharpPlus.Permissions.md)

The permissions to calculate from

`permission` [Permissions](DSharpPlus.Permissions.md)

permission you want to check

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_PermissionMethods_Revoke_DSharpPlus_Permissions_DSharpPlus_Permissions_"></a>Revoke\(Permissions, Permissions\)

Revokes permissions.

```csharp
public static Permissions Revoke(this Permissions p, Permissions revoke)
```

#### Parameters

`p` [Permissions](DSharpPlus.Permissions.md)

The permissions to take from.

`revoke` [Permissions](DSharpPlus.Permissions.md)

Permission to take.

#### Returns

[Permissions](DSharpPlus.Permissions.md)

