# Class DiscordRole

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a discord role, to which users can be assigned.

```csharp
public class DiscordRole : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordRole_Color"></a>Color

Gets the color of this role.

```csharp
[JsonIgnore]
public DiscordColor Color { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordRole_Emoji"></a>Emoji

The emoji associated with this role's icon, if set.

```csharp
public DiscordEmoji Emoji { get; }
```

#### Property Value

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

### <a id="DSharpPlus_Entities_DiscordRole_IconHash"></a>IconHash

The hash of this role's icon, if any.

```csharp
[JsonProperty("icon")]
public string IconHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRole_IconUrl"></a>IconUrl

The url for this role's icon, if set.

```csharp
public string IconUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRole_IsHoisted"></a>IsHoisted

Gets whether this role is hoisted.

```csharp
[JsonProperty("hoist", NullValueHandling = NullValueHandling.Ignore)]
public bool IsHoisted { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordRole_IsManaged"></a>IsManaged

Gets whether this role is managed by an integration.

```csharp
[JsonProperty("managed", NullValueHandling = NullValueHandling.Ignore)]
public bool IsManaged { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordRole_IsMentionable"></a>IsMentionable

Gets whether this role is mentionable.

```csharp
[JsonProperty("mentionable", NullValueHandling = NullValueHandling.Ignore)]
public bool IsMentionable { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordRole_Mention"></a>Mention

Gets a mention string for this role. If the role is mentionable, this string will mention all the users that belong to this role.

```csharp
public string Mention { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRole_Name"></a>Name

Gets the name of this role.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordRole_Permissions"></a>Permissions

Gets the permissions set for this role.

```csharp
[JsonProperty("permissions", NullValueHandling = NullValueHandling.Ignore)]
public Permissions Permissions { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

### <a id="DSharpPlus_Entities_DiscordRole_Position"></a>Position

Gets the position of this role in the role hierarchy.

```csharp
[JsonProperty("position", NullValueHandling = NullValueHandling.Ignore)]
public int Position { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordRole_Tags"></a>Tags

Gets the tags this role has.

```csharp
[JsonProperty("tags", NullValueHandling = NullValueHandling.Ignore)]
public DiscordRoleTags Tags { get; }
```

#### Property Value

[DiscordRoleTags](DSharpPlus.Entities.DiscordRoleTags.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordRole_CheckPermission_DSharpPlus_Permissions_"></a>CheckPermission\(Permissions\)

Checks whether this role has specific permissions.

```csharp
public PermissionLevel CheckPermission(Permissions permission)
```

#### Parameters

`permission` [Permissions](DSharpPlus.Permissions.md)

Permissions to check for.

#### Returns

[PermissionLevel](DSharpPlus.PermissionLevel.md)

Whether the permissions are allowed or not.

### <a id="DSharpPlus_Entities_DiscordRole_DeleteAsync_System_String_"></a>DeleteAsync\(string?\)

Deletes this role.

```csharp
public Task DeleteAsync(string? reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Reason as to why this role has been deleted.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordRole_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordRole_Equals_DSharpPlus_Entities_DiscordRole_"></a>Equals\(DiscordRole\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordRole e)
```

#### Parameters

`e` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

<xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordRole_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordRole_ModifyAsync_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Entities_DiscordColor__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>ModifyAsync\(string, Permissions?, DiscordColor?, bool?, bool?, string, Stream, DiscordEmoji\)

Updates this role.

```csharp
public Task ModifyAsync(string name = null, Permissions? permissions = null, DiscordColor? color = null, bool? hoist = null, bool? mentionable = null, string reason = null, Stream icon = null, DiscordEmoji emoji = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New role name

`permissions` [Permissions](DSharpPlus.Permissions.md)?

New role permissions

`color` [DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

New role color

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

New role hoist

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role is mentionable

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why we made this change

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordRole_ModifyAsync_System_Action_DSharpPlus_Net_Models_RoleEditModel__"></a>ModifyAsync\(Action<RoleEditModel\>\)

```csharp
public Task ModifyAsync(Action<RoleEditModel> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[RoleEditModel](DSharpPlus.Net.Models.RoleEditModel.md)\>

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the<xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordRole_ModifyPositionAsync_System_Int32_System_String_"></a>ModifyPositionAsync\(int, string\)

Modifies this role's position.

```csharp
public Task ModifyPositionAsync(int position, string reason = null)
```

#### Parameters

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

New position

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why we moved it

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordRole_ToString"></a>ToString\(\)

Returns a string representation of this role.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this role.

## Operators

### <a id="DSharpPlus_Entities_DiscordRole_op_Equality_DSharpPlus_Entities_DiscordRole_DSharpPlus_Entities_DiscordRole_"></a>operator ==\(DiscordRole, DiscordRole\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordRole e1, DiscordRole e2)
```

#### Parameters

`e1` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

First role to compare.

`e2` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Second role to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two roles are equal.

### <a id="DSharpPlus_Entities_DiscordRole_op_Inequality_DSharpPlus_Entities_DiscordRole_DSharpPlus_Entities_DiscordRole_"></a>operator \!=\(DiscordRole, DiscordRole\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordRole" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordRole e1, DiscordRole e2)
```

#### Parameters

`e1` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

First role to compare.

`e2` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Second role to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two roles are not equal.

