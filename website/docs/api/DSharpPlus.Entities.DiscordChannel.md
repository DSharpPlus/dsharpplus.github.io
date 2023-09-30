# Class DiscordChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a discord channel.

```csharp
[JsonConverter(typeof(DiscordForumChannelJsonConverter))]
public class DiscordChannel : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

###### Derived

[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md), 
[DiscordForumChannel](DSharpPlus.Entities.DiscordForumChannel.md), 
[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

###### Extension Methods

[DiscordClientExtensions.ConnectAsync\(DiscordChannel\)](DSharpPlus.VoiceNext.DiscordClientExtensions.md\#DSharpPlus\_VoiceNext\_DiscordClientExtensions\_ConnectAsync\_DSharpPlus\_Entities\_DiscordChannel\_), 
[DiscordClientExtensions.ConnectAsync\(DiscordChannel, LavalinkNodeConnection\)](DSharpPlus.Lavalink.DiscordClientExtensions.md\#DSharpPlus\_Lavalink\_DiscordClientExtensions\_ConnectAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Lavalink\_LavalinkNodeConnection\_), 
[ChannelExtensions.GetNextMessageAsync\(DiscordChannel, Func<DiscordMessage, bool\>, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_GetNextMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_System\_Func\_DSharpPlus\_Entities\_DiscordMessage\_System\_Boolean\_\_System\_Nullable\_System\_TimeSpan\_\_), 
[ChannelExtensions.GetNextMessageAsync\(DiscordChannel, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_GetNextMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_System\_Nullable\_System\_TimeSpan\_\_), 
[ChannelExtensions.GetNextMessageAsync\(DiscordChannel, DiscordUser, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_GetNextMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Entities\_DiscordUser\_System\_Nullable\_System\_TimeSpan\_\_), 
[ChannelExtensions.SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationEmojis, PaginationBehaviour?, PaginationDeletion?, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_SendPaginatedMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Entities\_DiscordUser\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Interactivity\_Page\_\_DSharpPlus\_Interactivity\_PaginationEmojis\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PaginationBehaviour\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PaginationDeletion\_\_System\_Nullable\_System\_TimeSpan\_\_), 
[ChannelExtensions.SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_SendPaginatedMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Entities\_DiscordUser\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Interactivity\_Page\_\_DSharpPlus\_Interactivity\_EventHandling\_PaginationButtons\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PaginationBehaviour\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_ButtonPaginationBehavior\_\_System\_Threading\_CancellationToken\_), 
[ChannelExtensions.SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationBehaviour?, ButtonPaginationBehavior?, CancellationToken\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_SendPaginatedMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Entities\_DiscordUser\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Interactivity\_Page\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PaginationBehaviour\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_ButtonPaginationBehavior\_\_System\_Threading\_CancellationToken\_), 
[ChannelExtensions.SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, PaginationButtons, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_SendPaginatedMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Entities\_DiscordUser\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Interactivity\_Page\_\_DSharpPlus\_Interactivity\_EventHandling\_PaginationButtons\_System\_Nullable\_System\_TimeSpan\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PaginationBehaviour\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_ButtonPaginationBehavior\_\_), 
[ChannelExtensions.SendPaginatedMessageAsync\(DiscordChannel, DiscordUser, IEnumerable<Page\>, TimeSpan?, PaginationBehaviour?, ButtonPaginationBehavior?\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_SendPaginatedMessageAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Entities\_DiscordUser\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Interactivity\_Page\_\_System\_Nullable\_System\_TimeSpan\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_PaginationBehaviour\_\_System\_Nullable\_DSharpPlus\_Interactivity\_Enums\_ButtonPaginationBehavior\_\_), 
[ChannelExtensions.WaitForUserTypingAsync\(DiscordChannel, DiscordUser, TimeSpan?\)](DSharpPlus.Interactivity.Extensions.ChannelExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ChannelExtensions\_WaitForUserTypingAsync\_DSharpPlus\_Entities\_DiscordChannel\_DSharpPlus\_Entities\_DiscordUser\_System\_Nullable\_System\_TimeSpan\_\_)

## Properties

### <a id="DSharpPlus_Entities_DiscordChannel_Bitrate"></a>Bitrate

Gets this channel's bitrate. This is applicable to voice channels only.

```csharp
[JsonProperty("bitrate", NullValueHandling = NullValueHandling.Ignore)]
public int? Bitrate { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordChannel_Children"></a>Children

Gets this channel's children. This applies only to channel categories.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordChannel> Children { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordChannel_Guild"></a>Guild

Gets the guild to which this channel belongs.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordChannel_GuildId"></a>GuildId

Gets ID of the guild to which this channel belongs.

```csharp
[JsonProperty("guild_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordChannel_IsCategory"></a>IsCategory

Gets whether this channel is a channel category.

```csharp
[JsonIgnore]
public bool IsCategory { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordChannel_IsNSFW"></a>IsNSFW

Gets whether this channel is an NSFW channel.

```csharp
[JsonProperty("nsfw")]
public bool IsNSFW { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordChannel_IsPrivate"></a>IsPrivate

Gets whether this channel is a DM channel.

```csharp
[JsonIgnore]
public bool IsPrivate { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordChannel_IsThread"></a>IsThread

Gets whether this channel is a thread.

```csharp
[JsonIgnore]
public bool IsThread { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordChannel_LastMessageId"></a>LastMessageId

Gets the ID of the last message sent in this channel. This is applicable to text channels only.

```csharp
[JsonProperty("last_message_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? LastMessageId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

#### Remarks

For forum posts, this ID may point to an invalid mesage (e.g. the OP deleted the initial forum message).

### <a id="DSharpPlus_Entities_DiscordChannel_LastPinTimestamp"></a>LastPinTimestamp

Gets when the last pinned message was pinned.

```csharp
[JsonProperty("last_pin_timestamp", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? LastPinTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordChannel_Mention"></a>Mention

Gets this channel's mention string.

```csharp
[JsonIgnore]
public string Mention { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordChannel_Name"></a>Name

Gets the name of this channel.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordChannel_Parent"></a>Parent

Gets the category that contains this channel. For threads, gets the channel this thread was created in.

```csharp
[JsonIgnore]
public DiscordChannel Parent { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordChannel_ParentId"></a>ParentId

Gets ID of the category that contains this channel. For threads, gets the ID of the channel this thread was created in.

```csharp
[JsonProperty("parent_id", NullValueHandling = NullValueHandling.Include)]
public ulong? ParentId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordChannel_PerUserRateLimit"></a>PerUserRateLimit

<p>Gets the slow mode delay configured for this channel.</p>
<p>All bots, as well as users with <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permissions in the channel are exempt from slow mode.</p>

```csharp
[JsonProperty("rate_limit_per_user")]
public int? PerUserRateLimit { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordChannel_PermissionOverwrites"></a>PermissionOverwrites

Gets a collection of permission overwrites for this channel.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordOverwrite> PermissionOverwrites { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordOverwrite](DSharpPlus.Entities.DiscordOverwrite.md)\>

### <a id="DSharpPlus_Entities_DiscordChannel_Position"></a>Position

Gets the position of this channel.

```csharp
[JsonProperty("position", NullValueHandling = NullValueHandling.Ignore)]
public int Position { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordChannel_QualityMode"></a>QualityMode

Gets this channel's video quality mode. This is applicable to voice channels only.

```csharp
[JsonProperty("video_quality_mode", NullValueHandling = NullValueHandling.Ignore)]
public VideoQualityMode? QualityMode { get; }
```

#### Property Value

[VideoQualityMode](DSharpPlus.VideoQualityMode.md)?

### <a id="DSharpPlus_Entities_DiscordChannel_RtcRegion"></a>RtcRegion

Gets this channel's region override (if voice channel).

```csharp
[JsonIgnore]
public DiscordVoiceRegion RtcRegion { get; }
```

#### Property Value

[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

### <a id="DSharpPlus_Entities_DiscordChannel_Threads"></a>Threads

Gets this channel's threads. This applies only to text and news channels.

```csharp
[JsonIgnore]
public IReadOnlyList<DiscordThreadChannel> Threads { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordChannel_Topic"></a>Topic

Gets the channel's topic. This is applicable to text channels only.

```csharp
[JsonProperty("topic", NullValueHandling = NullValueHandling.Ignore)]
public string Topic { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordChannel_Type"></a>Type

Gets the type of this channel.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public virtual ChannelType Type { get; }
```

#### Property Value

[ChannelType](DSharpPlus.ChannelType.md)

### <a id="DSharpPlus_Entities_DiscordChannel_UserLimit"></a>UserLimit

Gets this channel's user limit. This is applicable to voice channels only.

```csharp
[JsonProperty("user_limit", NullValueHandling = NullValueHandling.Ignore)]
public int? UserLimit { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordChannel_UserPermissions"></a>UserPermissions

Gets the permissions of the user who invoked the command in this channel.
<p>Only sent on the resolved channels of interaction responses for application commands.</p>

```csharp
[JsonProperty("permissions")]
public Permissions? UserPermissions { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)?

### <a id="DSharpPlus_Entities_DiscordChannel_Users"></a>Users

Gets the list of members currently in the channel (if voice channel), or members who can see the channel (otherwise).

```csharp
[JsonIgnore]
public virtual IReadOnlyList<DiscordMember> Users { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

## Methods

### <a id="DSharpPlus_Entities_DiscordChannel_AddOverwriteAsync_DSharpPlus_Entities_DiscordMember_DSharpPlus_Permissions_DSharpPlus_Permissions_System_String_"></a>AddOverwriteAsync\(DiscordMember, Permissions, Permissions, string\)

Adds a channel permission overwrite for specified member.

```csharp
public Task AddOverwriteAsync(DiscordMember member, Permissions allow = Permissions.None, Permissions deny = Permissions.None, string reason = null)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to have the permission added.

`allow` [Permissions](DSharpPlus.Permissions.md)

The permissions to allow.

`deny` [Permissions](DSharpPlus.Permissions.md)

The permissions to deny.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_AddOverwriteAsync_DSharpPlus_Entities_DiscordRole_DSharpPlus_Permissions_DSharpPlus_Permissions_System_String_"></a>AddOverwriteAsync\(DiscordRole, Permissions, Permissions, string\)

Adds a channel permission overwrite for specified role.

```csharp
public Task AddOverwriteAsync(DiscordRole role, Permissions allow = Permissions.None, Permissions deny = Permissions.None, string reason = null)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

The role to have the permission added.

`allow` [Permissions](DSharpPlus.Permissions.md)

The permissions to allow.

`deny` [Permissions](DSharpPlus.Permissions.md)

The permissions to deny.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_CloneAsync_System_String_"></a>CloneAsync\(string\)

Clones this channel. This operation will create a channel with identical settings to this one. Note that this will not copy messages.

```csharp
public Task<DiscordChannel> CloneAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

Newly-created channel.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_CreateGuildEventAsync_System_String_System_String_DSharpPlus_Entities_ScheduledGuildEventPrivacyLevel_System_DateTimeOffset_System_Nullable_System_DateTimeOffset__"></a>CreateGuildEventAsync\(string, string, ScheduledGuildEventPrivacyLevel, DateTimeOffset, DateTimeOffset?\)

Creates an event bound to this channel.

```csharp
public Task<DiscordScheduledGuildEvent> CreateGuildEventAsync(string name, string description, ScheduledGuildEventPrivacyLevel privacyLevel, DateTimeOffset start, DateTimeOffset? end)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the event, up to 100 characters.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of this event, up to 1000 characters.

`privacyLevel` [ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)

The privacy level. Currently only <xref href="DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.GuildOnly" data-throw-if-not-resolved="false"></xref> is supported

`start` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

When this event starts.

`end` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

When this event ends. External events require an end time.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The created event.

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

### <a id="DSharpPlus_Entities_DiscordChannel_CreateInviteAsync_System_Int32_System_Int32_System_Boolean_System_Boolean_System_String_System_Nullable_DSharpPlus_InviteTargetType__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>CreateInviteAsync\(int, int, bool, bool, string, InviteTargetType?, ulong?, ulong?\)

Create a new invite object

```csharp
public Task<DiscordInvite> CreateInviteAsync(int max_age = 86400, int max_uses = 0, bool temporary = false, bool unique = false, string reason = null, InviteTargetType? targetType = null, ulong? targetUserId = null, ulong? targetApplicationId = null)
```

#### Parameters

`max\_age` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Duration of invite in seconds before expiry, or 0 for never.  Defaults to 86400.

`max\_uses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Max number of uses or 0 for unlimited.  Defaults to 0

`temporary` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this invite only grants temporary membership.  Defaults to false.

`unique` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

If true, don't try to reuse a similar invite (useful for creating many unique one time use invites)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

`targetType` [InviteTargetType](DSharpPlus.InviteTargetType.md)?

The target type of the invite, for stream and embedded application invites.

`targetUserId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target user.

`targetApplicationId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target application.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.CreateInstantInvite" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_CreateStageInstanceAsync_System_String_System_Nullable_DSharpPlus_PrivacyLevel__System_String_"></a>CreateStageInstanceAsync\(string, PrivacyLevel?, string\)

Creates a stage instance in this stage channel.

```csharp
public Task<DiscordStageInstance> CreateStageInstanceAsync(string topic, PrivacyLevel? privacyLevel = null, string reason = null)
```

#### Parameters

`topic` [string](https://learn.microsoft.com/dotnet/api/system.string)

The topic of the stage instance.

`privacyLevel` [PrivacyLevel](DSharpPlus.PrivacyLevel.md)?

The privacy level of the stage instance.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason the stage instance was created.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The created stage instance.

### <a id="DSharpPlus_Entities_DiscordChannel_CreateThreadAsync_DSharpPlus_Entities_DiscordMessage_System_String_DSharpPlus_AutoArchiveDuration_System_String_"></a>CreateThreadAsync\(DiscordMessage, string, AutoArchiveDuration, string\)

Creates a new thread within this channel from the given message.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(DiscordMessage message, string name, AutoArchiveDuration archiveAfter, string reason = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to create the thread from.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration of the thread.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

The created thread.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel or message does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_CreateThreadAsync_System_String_DSharpPlus_AutoArchiveDuration_DSharpPlus_ChannelType_System_String_"></a>CreateThreadAsync\(string, AutoArchiveDuration, ChannelType, string\)

Creates a new thread within this channel.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(string name, AutoArchiveDuration archiveAfter, ChannelType threadType, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration of the thread.

`threadType` [ChannelType](DSharpPlus.ChannelType.md)

The type of thread to create, either a public, news or, private thread.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

The created thread.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel or message does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_CreateWebhookAsync_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__System_String_"></a>CreateWebhookAsync\(string, Optional<Stream\>, string\)

Create a new webhook

```csharp
public Task<DiscordWebhook> CreateWebhookAsync(string name, Optional<Stream> avatar = default, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the webhook.

`avatar` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

The image for the default webhook avatar.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_CrosspostMessageAsync_DSharpPlus_Entities_DiscordMessage_"></a>CrosspostMessageAsync\(DiscordMessage\)

Publishes a message in a news channel to following channels

```csharp
public Task<DiscordMessage> CrosspostMessageAsync(DiscordMessage message)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to publish

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message has already been crossposted

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> and/or <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref>

### <a id="DSharpPlus_Entities_DiscordChannel_DeleteAsync_System_String_"></a>DeleteAsync\(string\)

Deletes a guild channel

```csharp
public Task DeleteAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_DeleteMessageAsync_DSharpPlus_Entities_DiscordMessage_System_String_"></a>DeleteMessageAsync\(DiscordMessage, string\)

Deletes a message

```csharp
public Task DeleteMessageAsync(DiscordMessage message, string reason = null)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The message to be deleted.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_DeleteMessagesAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordMessage__System_String_"></a>DeleteMessagesAsync\(IEnumerable<DiscordMessage\>, string\)

Deletes multiple messages if they are less than 14 days old.  If they are older, none of the messages will be deleted and you will receive a <xref href="DSharpPlus.Exceptions.BadRequestException" data-throw-if-not-resolved="false"></xref> error.

```csharp
public Task DeleteMessagesAsync(IEnumerable<DiscordMessage> messages, string reason = null)
```

#### Parameters

`messages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

A collection of messages to delete.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_DeleteOverwriteAsync_DSharpPlus_Entities_DiscordMember_System_String_"></a>DeleteOverwriteAsync\(DiscordMember, string\)

Deletes a channel permission overwrite for the specified member.

```csharp
public Task DeleteOverwriteAsync(DiscordMember member, string reason = null)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to have the permission deleted.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_DeleteOverwriteAsync_DSharpPlus_Entities_DiscordRole_System_String_"></a>DeleteOverwriteAsync\(DiscordRole, string\)

Deletes a channel permission overwrite for the specified role.

```csharp
public Task DeleteOverwriteAsync(DiscordRole role, string reason = null)
```

#### Parameters

`role` [DiscordRole](DSharpPlus.Entities.DiscordRole.md)

The role to have the permission deleted.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_DeleteStageInstanceAsync_System_String_"></a>DeleteStageInstanceAsync\(string\)

Deletes the stage instance in this stage channel.

```csharp
public Task DeleteStageInstanceAsync(string reason = null)
```

#### Parameters

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason the stage instance was deleted.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordChannel_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordChannel_Equals_DSharpPlus_Entities_DiscordChannel_"></a>Equals\(DiscordChannel\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordChannel e)
```

#### Parameters

`e` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

<xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordChannel_FollowAsync_DSharpPlus_Entities_DiscordChannel_"></a>FollowAsync\(DiscordChannel\)

Follows a news channel

```csharp
public Task<DiscordFollowedChannel> FollowAsync(DiscordChannel targetChannel)
```

#### Parameters

`targetChannel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to crosspost messages to

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordFollowedChannel](DSharpPlus.Entities.DiscordFollowedChannel.md)\>

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when trying to follow a non-news channel

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> on the target channel

### <a id="DSharpPlus_Entities_DiscordChannel_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordChannel_GetInvitesAsync"></a>GetInvitesAsync\(\)

Returns a list of invite objects

```csharp
public Task<IReadOnlyList<DiscordInvite>> GetInvitesAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.CreateInstantInvite" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_GetMessageAsync_System_UInt64_System_Boolean_"></a>GetMessageAsync\(ulong, bool\)

Returns a specific message

```csharp
public Task<DiscordMessage> GetMessageAsync(ulong id, bool skipCache = false)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message

`skipCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Remarks

Cached message objects will not be returned if <xref href="DSharpPlus.DiscordConfiguration.MessageCacheSize" data-throw-if-not-resolved="false"></xref> is set to zero, if the client does not have the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordIntents.DirectMessages" data-throw-if-not-resolved="false"></xref> intents, or if the discord client is a <xref href="DSharpPlus.DiscordShardedClient" data-throw-if-not-resolved="false"></xref>.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ReadMessageHistory" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_GetMessagesAfterAsync_System_UInt64_System_Int32_"></a>GetMessagesAfterAsync\(ulong, int\)

Returns a list of messages after a certain message.
<param name="limit">The amount of messages to fetch.</param>
<param name="after">Message to fetch after from.</param>

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetMessagesAfterAsync(ulong after, int limit = 100)
```

#### Parameters

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AccessChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_GetMessagesAroundAsync_System_UInt64_System_Int32_"></a>GetMessagesAroundAsync\(ulong, int\)

Returns a list of messages around a certain message.
<param name="limit">The amount of messages to fetch.</param>
<param name="around">Message to fetch around from.</param>

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetMessagesAroundAsync(ulong around, int limit = 100)
```

#### Parameters

`around` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AccessChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_GetMessagesAsync_System_Int32_"></a>GetMessagesAsync\(int\)

Returns a list of messages from the last message in the channel.
<param name="limit">The amount of messages to fetch.</param>

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetMessagesAsync(int limit = 100)
```

#### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AccessChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_GetMessagesBeforeAsync_System_UInt64_System_Int32_"></a>GetMessagesBeforeAsync\(ulong, int\)

Returns a list of messages before a certain message.
<param name="limit">The amount of messages to fetch.</param>
<param name="before">Message to fetch before from.</param>

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetMessagesBeforeAsync(ulong before, int limit = 100)
```

#### Parameters

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AccessChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_GetPinnedMessagesAsync"></a>GetPinnedMessagesAsync\(\)

Returns all pinned messages

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetPinnedMessagesAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.AccessChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_GetStageInstanceAsync"></a>GetStageInstanceAsync\(\)

Gets the stage instance in this stage channel.

```csharp
public Task<DiscordStageInstance> GetStageInstanceAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The stage instance in the channel.

### <a id="DSharpPlus_Entities_DiscordChannel_GetWebhooksAsync"></a>GetWebhooksAsync\(\)

Returns a list of webhooks

```csharp
public Task<IReadOnlyList<DiscordWebhook>> GetWebhooksAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_ListJoinedPrivateArchivedThreadsAsync_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListJoinedPrivateArchivedThreadsAsync\(DateTimeOffset?, int\)

Gets the private and archived threads that the current member has joined in this channel.

```csharp
public Task<ThreadQueryResult> ListJoinedPrivateArchivedThreadsAsync(DateTimeOffset? before = null, int limit = 0)
```

#### Parameters

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

A <xref href="DSharpPlus.Entities.ThreadQueryResult" data-throw-if-not-resolved="false"></xref> containing the threads for this query and if an other call will yield more threads.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ReadMessageHistory" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_ListPrivateArchivedThreadsAsync_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListPrivateArchivedThreadsAsync\(DateTimeOffset?, int\)

Gets the threads that are private and archived for this channel.

```csharp
public Task<ThreadQueryResult> ListPrivateArchivedThreadsAsync(DateTimeOffset? before = null, int limit = 0)
```

#### Parameters

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

A <xref href="DSharpPlus.Entities.ThreadQueryResult" data-throw-if-not-resolved="false"></xref> containing the threads for this query and if an other call will yield more threads.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ReadMessageHistory" data-throw-if-not-resolved="false"></xref> and the <xref href="DSharpPlus.Permissions.ManageThreads" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_ListPublicArchivedThreadsAsync_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListPublicArchivedThreadsAsync\(DateTimeOffset?, int\)

Gets the threads that are public and archived for this channel.

```csharp
public Task<ThreadQueryResult> ListPublicArchivedThreadsAsync(DateTimeOffset? before = null, int limit = 0)
```

#### Parameters

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

A <xref href="DSharpPlus.Entities.ThreadQueryResult" data-throw-if-not-resolved="false"></xref> containing the threads for this query and if an other call will yield more threads.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ReadMessageHistory" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_ModifyAsync_System_Action_DSharpPlus_Net_Models_ChannelEditModel__"></a>ModifyAsync\(Action<ChannelEditModel\>\)

Modifies the current channel.

```csharp
public Task ModifyAsync(Action<ChannelEditModel> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ChannelEditModel](DSharpPlus.Net.Models.ChannelEditModel.md)\>

Action to perform on this channel

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_ModifyPositionAsync_System_Int32_System_String_System_Nullable_System_Boolean__System_Nullable_System_UInt64__"></a>ModifyPositionAsync\(int, string, bool?, ulong?\)

Updates the channel position

```csharp
public Task ModifyPositionAsync(int position, string reason = null, bool? lockPermissions = null, ulong? parentId = null)
```

#### Parameters

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Position the channel should be moved to.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

`lockPermissions` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to sync channel permissions with the parent, if moving to a new category.

`parentId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The new parent ID if the channel is to be moved to a new category.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_ModifyStageInstanceAsync_System_Action_DSharpPlus_Net_Models_StageInstanceEditModel__"></a>ModifyStageInstanceAsync\(Action<StageInstanceEditModel\>\)

Modifies the stage instance in this stage channel.

```csharp
public Task<DiscordStageInstance> ModifyStageInstanceAsync(Action<StageInstanceEditModel> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StageInstanceEditModel](DSharpPlus.Net.Models.StageInstanceEditModel.md)\>

Action to perform.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The modified stage instance.

### <a id="DSharpPlus_Entities_DiscordChannel_PermissionsFor_DSharpPlus_Entities_DiscordMember_"></a>PermissionsFor\(DiscordMember\)

Calculates permissions for a given member.

```csharp
public Permissions PermissionsFor(DiscordMember mbr)
```

#### Parameters

`mbr` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Member to calculate permissions for.

#### Returns

[Permissions](DSharpPlus.Permissions.md)

Calculated permissions for a given member.

### <a id="DSharpPlus_Entities_DiscordChannel_PlaceMemberAsync_DSharpPlus_Entities_DiscordMember_"></a>PlaceMemberAsync\(DiscordMember\)

Moves a member to this voice channel

```csharp
public Task PlaceMemberAsync(DiscordMember member)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to be moved.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.MoveMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exists or if the Member does not exists.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_System_String_"></a>SendMessageAsync\(string\)

Sends a message to this channel.

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

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordEmbed\)

Sends a message to this channel.

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

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(string, DiscordEmbed\)

Sends a message to this channel.

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

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_DSharpPlus_Entities_DiscordMessageBuilder_"></a>SendMessageAsync\(DiscordMessageBuilder\)

Sends a message to this channel.

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordMessageBuilder builder)
```

#### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The builder with all the items to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_SendMessageAsync_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>SendMessageAsync\(Action<DiscordMessageBuilder\>\)

Sends a message to this channel.

```csharp
public Task<DiscordMessage> SendMessageAsync(Action<DiscordMessageBuilder> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The builder with all the items to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The sent message.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission TTS is true and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_ToString"></a>ToString\(\)

Returns a string representation of this channel.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this channel.

### <a id="DSharpPlus_Entities_DiscordChannel_TriggerTypingAsync"></a>TriggerTypingAsync\(\)

Post a typing indicator

```csharp
public Task TriggerTypingAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordChannel_UpdateCurrentUserVoiceStateAsync_System_Nullable_System_Boolean__System_Nullable_System_DateTimeOffset__"></a>UpdateCurrentUserVoiceStateAsync\(bool?, DateTimeOffset?\)

Updates the current user's suppress state in this channel, if stage channel.

```csharp
public Task UpdateCurrentUserVoiceStateAsync(bool? suppress, DateTimeOffset? requestToSpeakTimestamp = null)
```

#### Parameters

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the suppress state.

`requestToSpeakTimestamp` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Sets the time the user requested to speak.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the channel is not a stage channel.

## Operators

### <a id="DSharpPlus_Entities_DiscordChannel_op_Equality_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordChannel_"></a>operator ==\(DiscordChannel, DiscordChannel\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordChannel e1, DiscordChannel e2)
```

#### Parameters

`e1` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

First channel to compare.

`e2` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Second channel to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two channels are equal.

### <a id="DSharpPlus_Entities_DiscordChannel_op_Inequality_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordChannel_"></a>operator \!=\(DiscordChannel, DiscordChannel\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordChannel" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordChannel e1, DiscordChannel e2)
```

#### Parameters

`e1` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

First channel to compare.

`e2` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Second channel to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two channels are not equal.

