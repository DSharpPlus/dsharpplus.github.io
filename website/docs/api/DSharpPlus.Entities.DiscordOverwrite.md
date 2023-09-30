# Class DiscordOverwrite

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a permission overwrite for a channel.

```csharp
public class DiscordOverwrite : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordOverwrite](DSharpPlus.Entities.DiscordOverwrite.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordOverwrite_Allowed"></a>Allowed

Gets the allowed permission set.

```csharp
[JsonProperty("allow", NullValueHandling = NullValueHandling.Ignore)]
public Permissions Allowed { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

### <a id="DSharpPlus_Entities_DiscordOverwrite_Denied"></a>Denied

Gets the denied permission set.

```csharp
[JsonProperty("deny", NullValueHandling = NullValueHandling.Ignore)]
public Permissions Denied { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

### <a id="DSharpPlus_Entities_DiscordOverwrite_Type"></a>Type

Gets the type of the overwrite. Either "role" or "member".

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public OverwriteType Type { get; }
```

#### Property Value

[OverwriteType](DSharpPlus.OverwriteType.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordOverwrite_CheckPermission_DSharpPlus_Permissions_"></a>CheckPermission\(Permissions\)

Checks whether given permissions are allowed, denied, or not set.

```csharp
public PermissionLevel CheckPermission(Permissions permission)
```

#### Parameters

`permission` [Permissions](DSharpPlus.Permissions.md)

Permissions to check.

#### Returns

[PermissionLevel](DSharpPlus.PermissionLevel.md)

Whether given permissions are allowed, denied, or not set.

### <a id="DSharpPlus_Entities_DiscordOverwrite_DeleteAsync_System_String_"></a>DeleteAsync\(string\)

Deletes this channel overwrite.

```csharp
public Task DeleteAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason as to why this overwrite gets deleted.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordOverwrite_GetMemberAsync"></a>GetMemberAsync\(\)

Gets the DiscordMember that is affected by this overwrite.

```csharp
public Task<DiscordMember> GetMemberAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

The DiscordMember that is affected by this overwrite

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AccessChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the overwrite does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordOverwrite_GetRoleAsync"></a>GetRoleAsync\(\)

Gets the DiscordRole that is affected by this overwrite.

```csharp
public Task<DiscordRole> GetRoleAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The DiscordRole that is affected by this overwrite

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordOverwrite_UpdateAsync_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Permissions__System_String_"></a>UpdateAsync\(Permissions?, Permissions?, string\)

Updates this channel overwrite.

```csharp
public Task UpdateAsync(Permissions? allow = null, Permissions? deny = null, string reason = null)
```

#### Parameters

`allow` [Permissions](DSharpPlus.Permissions.md)?

Permissions that are allowed.

`deny` [Permissions](DSharpPlus.Permissions.md)?

Permissions that are denied.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason as to why you made this change.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the overwrite does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

