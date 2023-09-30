# Class DiscordUser

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord user.

```csharp
public class DiscordUser : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

###### Derived

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordUser_AvatarHash"></a>AvatarHash

Gets the user's avatar hash.

```csharp
[JsonProperty("avatar", NullValueHandling = NullValueHandling.Ignore)]
public virtual string AvatarHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_AvatarUrl"></a>AvatarUrl

Gets the user's avatar URL.

```csharp
[JsonIgnore]
public string AvatarUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_BannerColor"></a>BannerColor

Gets the user's banner color, if set. Mutually exclusive with <xref href="DSharpPlus.Entities.DiscordUser.BannerHash" data-throw-if-not-resolved="false"></xref>.

```csharp
public virtual DiscordColor? BannerColor { get; }
```

#### Property Value

[DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

### <a id="DSharpPlus_Entities_DiscordUser_BannerHash"></a>BannerHash

Gets the user's profile banner hash. Mutually exclusive with <xref href="DSharpPlus.Entities.DiscordUser.BannerColor" data-throw-if-not-resolved="false"></xref>.

```csharp
[JsonProperty("banner", NullValueHandling = NullValueHandling.Ignore)]
public virtual string BannerHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_BannerUrl"></a>BannerUrl

Gets the user's banner url.

```csharp
[JsonIgnore]
public string BannerUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_DefaultAvatarUrl"></a>DefaultAvatarUrl

Gets the URL of default avatar for this user.

```csharp
[JsonIgnore]
public string DefaultAvatarUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_Discriminator"></a>Discriminator

Gets the user's 4-digit discriminator.

```csharp
[JsonProperty("discriminator", NullValueHandling = NullValueHandling.Ignore)]
public virtual string Discriminator { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

#### Remarks

As of May 15th, 2023, Discord has begun phasing out discriminators in favor of handles (@username); this property will return "0" for migrated accounts.

### <a id="DSharpPlus_Entities_DiscordUser_Email"></a>Email

Gets the user's email address.
<p>This is only present in OAuth.</p>

```csharp
[JsonProperty("email", NullValueHandling = NullValueHandling.Ignore)]
public virtual string Email { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_Flags"></a>Flags

Gets the user's flags.

```csharp
[JsonProperty("public_flags", NullValueHandling = NullValueHandling.Ignore)]
public virtual UserFlags? Flags { get; }
```

#### Property Value

[UserFlags](DSharpPlus.UserFlags.md)?

### <a id="DSharpPlus_Entities_DiscordUser_GlobalName"></a>GlobalName

Gets this user's global display name.

```csharp
[JsonProperty("global_name", NullValueHandling = NullValueHandling.Ignore)]
public virtual string GlobalName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

#### Remarks

A global display name differs from a username in that it acts like a nickname, but is not specific to a single guild.
Nicknames in servers however still take precedence over global names, which take precedence over usernames.

### <a id="DSharpPlus_Entities_DiscordUser_IsBot"></a>IsBot

Gets whether the user is a bot.

```csharp
[JsonProperty("bot", NullValueHandling = NullValueHandling.Ignore)]
public virtual bool IsBot { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordUser_IsCurrent"></a>IsCurrent

Gets whether this user is the Client which created this object.

```csharp
[JsonIgnore]
public bool IsCurrent { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordUser_IsSystem"></a>IsSystem

Gets whether the user is an official Discord system user.

```csharp
[JsonProperty("system", NullValueHandling = NullValueHandling.Ignore)]
public bool? IsSystem { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordUser_Locale"></a>Locale

Gets the user's chosen language

```csharp
[JsonProperty("locale", NullValueHandling = NullValueHandling.Ignore)]
public virtual string Locale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_Mention"></a>Mention

Gets the user's mention string.

```csharp
[JsonIgnore]
public string Mention { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_MfaEnabled"></a>MfaEnabled

Gets whether the user has multi-factor authentication enabled.

```csharp
[JsonProperty("mfa_enabled", NullValueHandling = NullValueHandling.Ignore)]
public virtual bool? MfaEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordUser_OAuthFlags"></a>OAuthFlags

Gets the user's flags for OAuth.

```csharp
[JsonProperty("flags", NullValueHandling = NullValueHandling.Ignore)]
public virtual UserFlags? OAuthFlags { get; }
```

#### Property Value

[UserFlags](DSharpPlus.UserFlags.md)?

### <a id="DSharpPlus_Entities_DiscordUser_PremiumType"></a>PremiumType

Gets the user's premium type.

```csharp
[JsonProperty("premium_type", NullValueHandling = NullValueHandling.Ignore)]
public virtual PremiumType? PremiumType { get; }
```

#### Property Value

[PremiumType](DSharpPlus.PremiumType.md)?

### <a id="DSharpPlus_Entities_DiscordUser_Presence"></a>Presence

Gets this user's presence.

```csharp
[JsonIgnore]
public DiscordPresence Presence { get; }
```

#### Property Value

[DiscordPresence](DSharpPlus.Entities.DiscordPresence.md)

### <a id="DSharpPlus_Entities_DiscordUser_Username"></a>Username

Gets this user's username.

```csharp
[JsonProperty("username", NullValueHandling = NullValueHandling.Ignore)]
public virtual string Username { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordUser_Verified"></a>Verified

Gets whether the user is verified.
<p>This is only present in OAuth.</p>

```csharp
[JsonProperty("verified", NullValueHandling = NullValueHandling.Ignore)]
public virtual bool? Verified { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

## Methods

### <a id="DSharpPlus_Entities_DiscordUser_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordUser_Equals_DSharpPlus_Entities_DiscordUser_"></a>Equals\(DiscordUser\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordUser e)
```

#### Parameters

`e` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

<xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordUser_GetAvatarUrl_DSharpPlus_ImageFormat_System_UInt16_"></a>GetAvatarUrl\(ImageFormat, ushort\)

Gets the user's avatar URL, in requested format and size.

```csharp
public string GetAvatarUrl(ImageFormat imageFormat, ushort imageSize = 1024)
```

#### Parameters

`imageFormat` [ImageFormat](DSharpPlus.ImageFormat.md)

The image format of the avatar to get.

`imageSize` [ushort](https://learn.microsoft.com/dotnet/api/system.uint16)

The maximum size of the avatar. Must be a power of two, minimum 16, maximum 4096.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The URL of the user's avatar.

### <a id="DSharpPlus_Entities_DiscordUser_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordUser_ToString"></a>ToString\(\)

Returns a string representation of this user.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this user.

### <a id="DSharpPlus_Entities_DiscordUser_UnbanAsync_DSharpPlus_Entities_DiscordGuild_System_String_"></a>UnbanAsync\(DiscordGuild, string\)

Unbans this user from a guild.

```csharp
public Task UnbanAsync(DiscordGuild guild, string reason = null)
```

#### Parameters

`guild` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

Guild to unban this user from.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.BanMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the user does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## Operators

### <a id="DSharpPlus_Entities_DiscordUser_op_Equality_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordUser_"></a>operator ==\(DiscordUser, DiscordUser\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordUser e1, DiscordUser e2)
```

#### Parameters

`e1` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

First user to compare.

`e2` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

Second user to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two users are equal.

### <a id="DSharpPlus_Entities_DiscordUser_op_Inequality_DSharpPlus_Entities_DiscordUser_DSharpPlus_Entities_DiscordUser_"></a>operator \!=\(DiscordUser, DiscordUser\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordUser" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordUser e1, DiscordUser e2)
```

#### Parameters

`e1` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

First user to compare.

`e2` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

Second user to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two users are not equal.

