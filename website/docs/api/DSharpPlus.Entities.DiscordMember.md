# Class DiscordMember

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord guild member.

```csharp
public class DiscordMember : DiscordUser
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordUser](DSharpPlus.Entities.DiscordUser.md) ← 
[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

###### Inherited Members

[DiscordUser.Username](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Username), 
[DiscordUser.GlobalName](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_GlobalName), 
[DiscordUser.Discriminator](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Discriminator), 
[DiscordUser.BannerColor](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_BannerColor), 
[DiscordUser.BannerUrl](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_BannerUrl), 
[DiscordUser.BannerHash](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_BannerHash), 
[DiscordUser.AvatarHash](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_AvatarHash), 
[DiscordUser.AvatarUrl](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_AvatarUrl), 
[DiscordUser.DefaultAvatarUrl](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_DefaultAvatarUrl), 
[DiscordUser.IsBot](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_IsBot), 
[DiscordUser.MfaEnabled](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_MfaEnabled), 
[DiscordUser.IsSystem](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_IsSystem), 
[DiscordUser.Verified](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Verified), 
[DiscordUser.Email](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Email), 
[DiscordUser.PremiumType](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_PremiumType), 
[DiscordUser.Locale](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Locale), 
[DiscordUser.OAuthFlags](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_OAuthFlags), 
[DiscordUser.Flags](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Flags), 
[DiscordUser.Mention](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Mention), 
[DiscordUser.IsCurrent](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_IsCurrent), 
[DiscordUser.UnbanAsync\(DiscordGuild, string\)](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_UnbanAsync\_DSharpPlus\_Entities\_DiscordGuild\_System\_String\_), 
[DiscordUser.Presence](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Presence), 
[DiscordUser.GetAvatarUrl\(ImageFormat, ushort\)](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_GetAvatarUrl\_DSharpPlus\_ImageFormat\_System\_UInt16\_), 
[DiscordUser.ToString\(\)](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_ToString), 
[DiscordUser.Equals\(object\)](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Equals\_System\_Object\_), 
[DiscordUser.Equals\(DiscordUser\)](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_Equals\_DSharpPlus\_Entities\_DiscordUser\_), 
[DiscordUser.GetHashCode\(\)](DSharpPlus.Entities.DiscordUser.md\#DSharpPlus\_Entities\_DiscordUser\_GetHashCode), 
[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordMember_AvatarHash"></a>AvatarHash

Gets the member's avatar hash.

```csharp
[JsonIgnore]
public override string AvatarHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_BannerColor"></a>BannerColor

The color of this member's banner. Mutually exclusive with <xref href="DSharpPlus.Entities.DiscordMember.BannerHash" data-throw-if-not-resolved="false"></xref>.

```csharp
[JsonIgnore]
public override DiscordColor? BannerColor { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

### <a id="DSharpPlus_Entities_DiscordMember_BannerHash"></a>BannerHash

Gets the member's banner hash.

```csharp
[JsonIgnore]
public override string BannerHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_Color"></a>Color

Gets the color associated with this user's top color-giving role, otherwise 0 (no color).

```csharp
[JsonIgnore]
public DiscordColor Color { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)

### <a id="DSharpPlus_Entities_DiscordMember_CommunicationDisabledUntil"></a>CommunicationDisabledUntil

How long this member's communication will be suppressed for.

```csharp
[JsonProperty("communication_disabled_until", NullValueHandling = NullValueHandling.Include)]
public DateTimeOffset? CommunicationDisabledUntil { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordMember_Discriminator"></a>Discriminator

Gets the member's 4-digit discriminator.

```csharp
[JsonIgnore]
public override string Discriminator { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_DisplayName"></a>DisplayName

Gets this member's display name.

```csharp
[JsonIgnore]
public string DisplayName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_Email"></a>Email

Gets the member's email address.
<p>This is only present in OAuth.</p>

```csharp
[JsonIgnore]
public override string Email { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_Flags"></a>Flags

Gets the member's flags for OAuth.

```csharp
[JsonIgnore]
public override UserFlags? Flags { get; }
```

#### Property Value

[UserFlags](DSharpPlus.UserFlags.md)?

### <a id="DSharpPlus_Entities_DiscordMember_GlobalName"></a>GlobalName

Gets the member's global display name.

```csharp
[JsonIgnore]
public override string? GlobalName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordMember_Guild"></a>Guild

Gets the guild of which this member is a part of.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordMember_GuildAvatarHash"></a>GuildAvatarHash

Gets the member's avatar for the current guild.

```csharp
[JsonIgnore]
public string GuildAvatarHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_GuildAvatarUrl"></a>GuildAvatarUrl

Gets the members avatar url for the current guild.

```csharp
[JsonIgnore]
public string GuildAvatarUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_Hierarchy"></a>Hierarchy

Gets the member's position in the role hierarchy, which is the member's highest role's position. Returns <xref href="System.Int32.MaxValue" data-throw-if-not-resolved="false"></xref> for the guild's owner.

```csharp
[JsonIgnore]
public int Hierarchy { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordMember_IsBot"></a>IsBot

Gets whether the member is a bot.

```csharp
[JsonIgnore]
public override bool IsBot { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMember_IsDeafened"></a>IsDeafened

If the user is deafened

```csharp
[JsonProperty("is_deafened", NullValueHandling = NullValueHandling.Ignore)]
public bool IsDeafened { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMember_IsMuted"></a>IsMuted

If the user is muted

```csharp
[JsonProperty("is_muted", NullValueHandling = NullValueHandling.Ignore)]
public bool IsMuted { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMember_IsOwner"></a>IsOwner

Gets whether this member is the Guild owner.

```csharp
[JsonIgnore]
public bool IsOwner { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordMember_IsPending"></a>IsPending

If the user has passed the guild's Membership Screening requirements

```csharp
[JsonProperty("pending", NullValueHandling = NullValueHandling.Ignore)]
public bool? IsPending { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordMember_JoinedAt"></a>JoinedAt

Date the user joined the guild

```csharp
[JsonProperty("joined_at", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset JoinedAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordMember_Locale"></a>Locale

Gets the member's chosen language

```csharp
[JsonIgnore]
public override string Locale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_MfaEnabled"></a>MfaEnabled

Gets whether the member has multi-factor authentication enabled.

```csharp
[JsonIgnore]
public override bool? MfaEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordMember_Nickname"></a>Nickname

Gets this member's nickname.

```csharp
[JsonProperty("nick", NullValueHandling = NullValueHandling.Ignore)]
public string Nickname { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_OAuthFlags"></a>OAuthFlags

Gets the user's flags.

```csharp
[JsonIgnore]
public override UserFlags? OAuthFlags { get; }
```

#### Property Value

[UserFlags](DSharpPlus.UserFlags.md)?

### <a id="DSharpPlus_Entities_DiscordMember_Permissions"></a>Permissions

Gets the permissions for the current member.

```csharp
[JsonIgnore]
public Permissions Permissions { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)

### <a id="DSharpPlus_Entities_DiscordMember_PremiumSince"></a>PremiumSince

Date the user started boosting this server

```csharp
[JsonProperty("premium_since", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? PremiumSince { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordMember_Roles"></a>Roles

Gets the list of roles associated with this member.

```csharp
[JsonIgnore]
public IEnumerable<DiscordRole> Roles { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_Entities_DiscordMember_Username"></a>Username

Gets this member's username.

```csharp
[JsonIgnore]
public override string Username { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordMember_Verified"></a>Verified

Gets whether the member is verified.
<p>This is only present in OAuth.</p>

```csharp
[JsonIgnore]
public override bool? Verified { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordMember_VoiceState"></a>VoiceState

Gets this member's voice state.

```csharp
[JsonIgnore]
public DiscordVoiceState VoiceState { get; }
```

#### Property Value

[DiscordVoiceState](DSharpPlus.Entities.DiscordVoiceState.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordMember_BanAsync_System_Int32_System_String_"></a>BanAsync\(int, string\)

Bans a this member from their guild.

```csharp
public Task BanAsync(int delete_message_days = 0, string reason = null)
```

#### Parameters

`delete\_message\_days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How many days to remove messages from.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.BanMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_CreateDmChannelAsync"></a>CreateDmChannelAsync\(\)

Creates a direct message channel to this member.

```csharp
public Task<DiscordDmChannel> CreateDmChannelAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

Direct message channel to this member.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordMember_Equals_DSharpPlus_Entities_DiscordMember_"></a>Equals\(DiscordMember\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordMember e)
```

#### Parameters

`e` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

<xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordMember_GetGuildAvatarUrl_DSharpPlus_ImageFormat_System_UInt16_"></a>GetGuildAvatarUrl\(ImageFormat, ushort\)

Constructs the url for a guild member's avatar, defaulting to the user's avatar if none is set.

```csharp
public string GetGuildAvatarUrl(ImageFormat imageFormat, ushort imageSize = 1024)
```

#### Parameters

`imageFormat` [ImageFormat](DSharpPlus.ImageFormat.md)

The image format of the avatar to get.

`imageSize` [ushort](https://learn.microsoft.com/dotnet/api/system.uint16)

The maximum size of the avatar. Must be a power of two, minimum 16, maximum 4096.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The URL of the user's avatar.

### <a id="DSharpPlus_Entities_DiscordMember_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordMember_GrantRoleAsync_DSharpPlus_Entities_DiscordRole_System_String_"></a>GrantRoleAsync\(DiscordRole, string\)

Grants a role to the member.

```csharp
public Task GrantRoleAsync(DiscordRole role, string reason = null)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Role to grant.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_ModifyAsync_System_Action_DSharpPlus_Net_Models_MemberEditModel__"></a>ModifyAsync\(Action<MemberEditModel\>\)

Modifies this member.

```csharp
public Task ModifyAsync(Action<MemberEditModel> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[MemberEditModel](DSharpPlus.Net.Models.MemberEditModel.md)\>

Action to perform on this member.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageNicknames" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_PermissionsIn_DSharpPlus_Entities_DiscordChannel_"></a>PermissionsIn\(DiscordChannel\)

Calculates permissions in a given channel for this member.

```csharp
public Permissions PermissionsIn(DiscordChannel channel)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to calculate permissions for.

#### Returns

[Permissions](DSharpPlus.Permissions.md)

Calculated permissions for this member in the channel.

### <a id="DSharpPlus_Entities_DiscordMember_PlaceInAsync_DSharpPlus_Entities_DiscordChannel_"></a>PlaceInAsync\(DiscordChannel\)

Moves this member to the specified voice channel

```csharp
public Task PlaceInAsync(DiscordChannel channel)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.MoveMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_RemoveAsync_System_String_"></a>RemoveAsync\(string\)

Kicks this member from their guild.

```csharp
public Task RemoveAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Remarks

[alias="KickAsync"]

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.KickMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_ReplaceRolesAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>ReplaceRolesAsync\(IEnumerable<DiscordRole\>, string\)

Sets the member's roles to ones specified.

```csharp
public Task ReplaceRolesAsync(IEnumerable<DiscordRole> roles, string reason = null)
```

#### Parameters

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

Roles to set.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_RevokeRoleAsync_DSharpPlus_Entities_DiscordRole_System_String_"></a>RevokeRoleAsync\(DiscordRole, string\)

Revokes a role from a member.

```csharp
public Task RevokeRoleAsync(DiscordRole role, string reason = null)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Role to revoke.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_System_String_"></a>SendMessageAsync\(string\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

```csharp
public Task<DiscordMessage> SendMessageAsync(string content)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content of the message to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordEmbed\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordEmbed embed)
```

#### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(string, DiscordEmbed\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

```csharp
public Task<DiscordMessage> SendMessageAsync(string content, DiscordEmbed embed)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content of the message to send.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_SendMessageAsync_DSharpPlus_Entities_DiscordMessageBuilder_"></a>SendMessageAsync\(DiscordMessageBuilder\)

Sends a direct message to this member. Creates a direct message channel if one does not exist already.

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordMessageBuilder message)
```

#### Parameters

`message` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

Builder to with the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the member has the bot blocked, the member is no longer in the guild, or if the member has Allow DM from server members off.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_SetDeafAsync_System_Boolean_System_String_"></a>SetDeafAsync\(bool, string\)

Sets this member's voice deaf status.

```csharp
public Task SetDeafAsync(bool deaf, string reason = null)
```

#### Parameters

`deaf` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the member is to be deafened.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.DeafenMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_SetMuteAsync_System_Boolean_System_String_"></a>SetMuteAsync\(bool, string\)

Sets this member's voice mute status.

```csharp
public Task SetMuteAsync(bool mute, string reason = null)
```

#### Parameters

`mute` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the member is to be muted.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.MuteMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_TimeoutAsync_System_Nullable_System_DateTimeOffset__System_String_"></a>TimeoutAsync\(DateTimeOffset?, string\)

Times-out a member and restricts their ability to send messages, add reactions, speak in threads, and join voice channels.

```csharp
public Task TimeoutAsync(DateTimeOffset? until, string reason = null)
```

#### Parameters

`until` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

How long the timeout should last. Set to <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> or a time in the past to remove the timeout.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why this member is being restricted.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordMember_ToString"></a>ToString\(\)

Returns a string representation of this member.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this member.

### <a id="DSharpPlus_Entities_DiscordMember_UnbanAsync_System_String_"></a>UnbanAsync\(string\)

```csharp
public Task UnbanAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the<xref href="DSharpPlus.Permissions.BanMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordMember_UpdateVoiceStateAsync_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_Boolean__"></a>UpdateVoiceStateAsync\(DiscordChannel, bool?\)

Updates the member's suppress state in a stage channel.

```csharp
public Task UpdateVoiceStateAsync(DiscordChannel channel, bool? suppress)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel the member is currently in.

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the member's suppress state.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the channel in not a voice channel.

## Operators

### <a id="DSharpPlus_Entities_DiscordMember_op_Equality_DSharpPlus_Entities_DiscordMember_DSharpPlus_Entities_DiscordMember_"></a>operator ==\(DiscordMember, DiscordMember\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordMember e1, DiscordMember e2)
```

#### Parameters

`e1` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

First member to compare.

`e2` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Second member to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two members are equal.

### <a id="DSharpPlus_Entities_DiscordMember_op_Inequality_DSharpPlus_Entities_DiscordMember_DSharpPlus_Entities_DiscordMember_"></a>operator \!=\(DiscordMember, DiscordMember\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordMember e1, DiscordMember e2)
```

#### Parameters

`e1` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

First member to compare.

`e2` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Second member to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two members are not equal.

