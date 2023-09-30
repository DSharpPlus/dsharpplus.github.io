# Class DiscordInvite

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord invite.

```csharp
public class DiscordInvite
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordInvite_ApproximateMemberCount"></a>ApproximateMemberCount

Gets the approximate guild total member count for the invite.

```csharp
[JsonProperty("approximate_member_count")]
public int? ApproximateMemberCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordInvite_ApproximatePresenceCount"></a>ApproximatePresenceCount

Gets the approximate guild online member count for the invite.

```csharp
[JsonProperty("approximate_presence_count", NullValueHandling = NullValueHandling.Ignore)]
public int? ApproximatePresenceCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordInvite_Channel"></a>Channel

Gets the channel this invite is for.

```csharp
[JsonProperty("channel", NullValueHandling = NullValueHandling.Ignore)]
public DiscordInviteChannel Channel { get; }
```

#### Property Value

[DiscordInviteChannel](DSharpPlus.Entities.DiscordInviteChannel.md)

### <a id="DSharpPlus_Entities_DiscordInvite_Code"></a>Code

Gets the invite's code.

```csharp
[JsonProperty("code", NullValueHandling = NullValueHandling.Ignore)]
public string Code { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordInvite_CreatedAt"></a>CreatedAt

Gets the date and time this invite was created.

```csharp
[JsonProperty("created_at", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset CreatedAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordInvite_ExpiresAt"></a>ExpiresAt

Gets the expiration date of this invite.

```csharp
[JsonIgnore]
public DateTimeOffset? ExpiresAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordInvite_Guild"></a>Guild

Gets the guild this invite is for.

```csharp
[JsonProperty("guild", NullValueHandling = NullValueHandling.Ignore)]
public DiscordInviteGuild Guild { get; }
```

#### Property Value

[DiscordInviteGuild](DSharpPlus.Entities.DiscordInviteGuild.md)

### <a id="DSharpPlus_Entities_DiscordInvite_Inviter"></a>Inviter

Gets the user who created the invite.

```csharp
[JsonProperty("inviter", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUser Inviter { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_Entities_DiscordInvite_IsRevoked"></a>IsRevoked

Gets whether this invite is revoked.

```csharp
[JsonProperty("revoked", NullValueHandling = NullValueHandling.Ignore)]
public bool IsRevoked { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordInvite_IsTemporary"></a>IsTemporary

Gets whether this invite only grants temporary membership.

```csharp
[JsonProperty("temporary", NullValueHandling = NullValueHandling.Ignore)]
public bool IsTemporary { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordInvite_MaxAge"></a>MaxAge

Gets duration in seconds after which the invite expires.

```csharp
[JsonProperty("max_age", NullValueHandling = NullValueHandling.Ignore)]
public int MaxAge { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordInvite_MaxUses"></a>MaxUses

Gets the max number of times this invite can be used.

```csharp
[JsonProperty("max_uses", NullValueHandling = NullValueHandling.Ignore)]
public int MaxUses { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordInvite_StageInstance"></a>StageInstance

Gets stage instance data for this invite if it is for a stage instance channel.

```csharp
[JsonProperty("stage_instance")]
public DiscordStageInvite StageInstance { get; }
```

#### Property Value

[DiscordStageInvite](DSharpPlus.Entities.DiscordStageInvite.md)

### <a id="DSharpPlus_Entities_DiscordInvite_TargetApplication"></a>TargetApplication

Gets the partial embedded application to open for a voice channel.

```csharp
[JsonProperty("target_application", NullValueHandling = NullValueHandling.Ignore)]
public DiscordApplication TargetApplication { get; }
```

#### Property Value

[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

### <a id="DSharpPlus_Entities_DiscordInvite_TargetType"></a>TargetType

Gets the target application for this invite.

```csharp
[JsonProperty("target_type", NullValueHandling = NullValueHandling.Ignore)]
public InviteTargetType? TargetType { get; }
```

#### Property Value

[InviteTargetType](DSharpPlus.InviteTargetType.md)?

### <a id="DSharpPlus_Entities_DiscordInvite_TargetUser"></a>TargetUser

Gets the partial user that is currently livestreaming.

```csharp
[JsonProperty("target_user", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUser TargetUser { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_Entities_DiscordInvite_Uses"></a>Uses

Gets the number of times this invite has been used.

```csharp
[JsonProperty("uses", NullValueHandling = NullValueHandling.Ignore)]
public int Uses { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_Entities_DiscordInvite_DeleteAsync_System_String_"></a>DeleteAsync\(string\)

Deletes the invite.

```csharp
public Task<DiscordInvite> DeleteAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission or the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordInvite_ToString"></a>ToString\(\)

Converts this invite into an invite link.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

A discord.gg invite link.

