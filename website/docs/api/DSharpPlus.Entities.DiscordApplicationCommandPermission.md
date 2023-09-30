# Class DiscordApplicationCommandPermission

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a permission for a application command.

```csharp
public class DiscordApplicationCommandPermission
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordApplicationCommandPermission](DSharpPlus.Entities.DiscordApplicationCommandPermission.md)

## Constructors

### <a id="DSharpPlus_Entities_DiscordApplicationCommandPermission__ctor_DSharpPlus_Entities_DiscordRole_System_Boolean_"></a>DiscordApplicationCommandPermission\(DiscordRole, bool\)

Represents a permission for a application command.

```csharp
public DiscordApplicationCommandPermission(DiscordRole role, bool permission)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

The role to construct the permission for.

`permission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the command should be enabled for the role.

### <a id="DSharpPlus_Entities_DiscordApplicationCommandPermission__ctor_DSharpPlus_Entities_DiscordMember_System_Boolean_"></a>DiscordApplicationCommandPermission\(DiscordMember, bool\)

Represents a permission for a application command.

```csharp
public DiscordApplicationCommandPermission(DiscordMember member, bool permission)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to construct the permission for.

`permission` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the command should be enabled for the role.

## Properties

### <a id="DSharpPlus_Entities_DiscordApplicationCommandPermission_Id"></a>Id

The id of the role or the user this permission is for.

```csharp
[JsonProperty("id")]
public ulong Id { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordApplicationCommandPermission_Permission"></a>Permission

Gets whether the command is enabled for the role or user.

```csharp
[JsonProperty("permission")]
public bool Permission { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordApplicationCommandPermission_Type"></a>Type

Gets the type of the permission.

```csharp
[JsonProperty("type")]
public ApplicationCommandPermissionType Type { get; }
```

#### Property Value

[ApplicationCommandPermissionType](DSharpPlus.ApplicationCommandPermissionType.md)

