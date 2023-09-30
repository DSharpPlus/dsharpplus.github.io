# Class DiscordGuildEmoji

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordGuildEmoji : DiscordEmoji
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md) ← 
[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)

###### Inherited Members

[DiscordEmoji.Name](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_Name), 
[DiscordEmoji.Roles](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_Roles), 
[DiscordEmoji.RequiresColons](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_RequiresColons), 
[DiscordEmoji.IsManaged](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_IsManaged), 
[DiscordEmoji.IsAnimated](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_IsAnimated), 
[DiscordEmoji.Url](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_Url), 
[DiscordEmoji.IsAvailable](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_IsAvailable), 
[DiscordEmoji.GetDiscordName\(\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_GetDiscordName), 
[DiscordEmoji.ToString\(\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_ToString), 
[DiscordEmoji.Equals\(object\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_Equals\_System\_Object\_), 
[DiscordEmoji.Equals\(DiscordEmoji\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_Equals\_DSharpPlus\_Entities\_DiscordEmoji\_), 
[DiscordEmoji.GetHashCode\(\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_GetHashCode), 
[DiscordEmoji.IsValidUnicode\(string\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_IsValidUnicode\_System\_String\_), 
[DiscordEmoji.FromUnicode\(BaseDiscordClient, string\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_FromUnicode\_DSharpPlus\_BaseDiscordClient\_System\_String\_), 
[DiscordEmoji.FromUnicode\(string\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_FromUnicode\_System\_String\_), 
[DiscordEmoji.TryFromUnicode\(BaseDiscordClient, string, out DiscordEmoji\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_TryFromUnicode\_DSharpPlus\_BaseDiscordClient\_System\_String\_DSharpPlus\_Entities\_DiscordEmoji\_\_), 
[DiscordEmoji.TryFromUnicode\(string, out DiscordEmoji\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_TryFromUnicode\_System\_String\_DSharpPlus\_Entities\_DiscordEmoji\_\_), 
[DiscordEmoji.FromGuildEmote\(BaseDiscordClient, ulong\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_FromGuildEmote\_DSharpPlus\_BaseDiscordClient\_System\_UInt64\_), 
[DiscordEmoji.TryFromGuildEmote\(BaseDiscordClient, ulong, out DiscordEmoji\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_TryFromGuildEmote\_DSharpPlus\_BaseDiscordClient\_System\_UInt64\_DSharpPlus\_Entities\_DiscordEmoji\_\_), 
[DiscordEmoji.FromName\(BaseDiscordClient, string, bool\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_FromName\_DSharpPlus\_BaseDiscordClient\_System\_String\_System\_Boolean\_), 
[DiscordEmoji.TryFromName\(BaseDiscordClient, string, out DiscordEmoji\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_TryFromName\_DSharpPlus\_BaseDiscordClient\_System\_String\_DSharpPlus\_Entities\_DiscordEmoji\_\_), 
[DiscordEmoji.TryFromName\(BaseDiscordClient, string, bool, out DiscordEmoji\)](DSharpPlus.Entities.DiscordEmoji.md\#DSharpPlus\_Entities\_DiscordEmoji\_TryFromName\_DSharpPlus\_BaseDiscordClient\_System\_String\_System\_Boolean\_DSharpPlus\_Entities\_DiscordEmoji\_\_), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildEmoji_Guild"></a>Guild

Gets the guild to which this emoji belongs.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordGuildEmoji_User"></a>User

Gets the user that created this emoji.

```csharp
[JsonIgnore]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordGuildEmoji_DeleteAsync_System_String_"></a>DeleteAsync\(string\)

Deletes this emoji.

```csharp
public Task DeleteAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuildEmoji_ModifyAsync_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>ModifyAsync\(string, IEnumerable<DiscordRole\>, string\)

Modifies this emoji.

```csharp
public Task<DiscordGuildEmoji> ModifyAsync(string name, IEnumerable<DiscordRole> roles = null, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New name for this emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

Roles for which this emoji will be available. This works only if your application is whitelisted as integration.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

The modified emoji.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

