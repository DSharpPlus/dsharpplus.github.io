# Class DiscordGuild

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord guild.

```csharp
public class DiscordGuild : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuild_AfkChannel"></a>AfkChannel

Gets the guild's AFK voice channel.

```csharp
[JsonIgnore]
public DiscordChannel AfkChannel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_AfkTimeout"></a>AfkTimeout

Gets the guild's AFK timeout.

```csharp
[JsonProperty("afk_timeout", NullValueHandling = NullValueHandling.Ignore)]
public int AfkTimeout { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordGuild_ApplicationId"></a>ApplicationId

Gets the application ID of this guild if it is bot created.

```csharp
[JsonProperty("application_id")]
public ulong? ApplicationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordGuild_ApproximateMemberCount"></a>ApproximateMemberCount

Gets the approximate number of members in this guild, when using <xref href="DSharpPlus.DiscordClient.GetGuildAsync(System.UInt64%2cSystem.Nullable%7bSystem.Boolean%7d)" data-throw-if-not-resolved="false"></xref> and having <code class="paramref">withCounts</code> set to true.

```csharp
[JsonProperty("approximate_member_count", NullValueHandling = NullValueHandling.Ignore)]
public int? ApproximateMemberCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordGuild_ApproximatePresenceCount"></a>ApproximatePresenceCount

Gets the approximate number of presences in this guild, when using <xref href="DSharpPlus.DiscordClient.GetGuildAsync(System.UInt64%2cSystem.Nullable%7bSystem.Boolean%7d)" data-throw-if-not-resolved="false"></xref> and having <code class="paramref">withCounts</code> set to true.

```csharp
[JsonProperty("approximate_presence_count", NullValueHandling = NullValueHandling.Ignore)]
public int? ApproximatePresenceCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordGuild_Banner"></a>Banner

Gets this guild's banner hash, when applicable.

```csharp
[JsonProperty("banner")]
public string Banner { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_BannerUrl"></a>BannerUrl

Gets this guild's banner in url form.

```csharp
[JsonIgnore]
public string BannerUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_Channels"></a>Channels

Gets a dictionary of all the channels associated with this guild. The dictionary's key is the channel ID.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordChannel> Channels { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_CurrentMember"></a>CurrentMember

Gets the guild member for current user.

```csharp
[JsonIgnore]
public DiscordMember CurrentMember { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_Entities_DiscordGuild_DefaultMessageNotifications"></a>DefaultMessageNotifications

Gets the guild's default notification settings.

```csharp
[JsonProperty("default_message_notifications", NullValueHandling = NullValueHandling.Ignore)]
public DefaultMessageNotifications DefaultMessageNotifications { get; }
```

#### Property Value

[DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)

### <a id="DSharpPlus_Entities_DiscordGuild_Description"></a>Description

Gets the guild description, when applicable.

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_DiscoverySplashHash"></a>DiscoverySplashHash

Gets the guild discovery splash's hash.

```csharp
[JsonProperty("discovery_splash", NullValueHandling = NullValueHandling.Ignore)]
public string DiscoverySplashHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_DiscoverySplashUrl"></a>DiscoverySplashUrl

Gets the guild discovery splash's url.

```csharp
[JsonIgnore]
public string DiscoverySplashUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_Emojis"></a>Emojis

Gets a collection of this guild's emojis.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordEmoji> Emojis { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_EveryoneRole"></a>EveryoneRole

Gets the @everyone role for this guild.

```csharp
[JsonIgnore]
public DiscordRole EveryoneRole { get; }
```

#### Property Value

[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

### <a id="DSharpPlus_Entities_DiscordGuild_ExplicitContentFilter"></a>ExplicitContentFilter

Gets the guild's explicit content filter settings.

```csharp
[JsonProperty("explicit_content_filter")]
public ExplicitContentFilter ExplicitContentFilter { get; }
```

#### Property Value

[ExplicitContentFilter](DSharpPlus.Entities.ExplicitContentFilter.md)

### <a id="DSharpPlus_Entities_DiscordGuild_Features"></a>Features

Gets a collection of this guild's features.

```csharp
[JsonProperty("features", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<string> Features { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="DSharpPlus_Entities_DiscordGuild_IconHash"></a>IconHash

Gets the guild icon's hash.

```csharp
[JsonProperty("icon", NullValueHandling = NullValueHandling.Ignore)]
public string IconHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_IconUrl"></a>IconUrl

Gets the guild icon's url.

```csharp
[JsonIgnore]
public string IconUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_IsLarge"></a>IsLarge

Gets whether this guild is considered to be a large guild.

```csharp
[JsonProperty("large", NullValueHandling = NullValueHandling.Ignore)]
public bool IsLarge { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordGuild_IsNSFW"></a>IsNSFW

Gets whether this guild is designated as NSFW.

```csharp
[JsonProperty("nsfw", NullValueHandling = NullValueHandling.Ignore)]
public bool IsNSFW { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordGuild_IsOwner"></a>IsOwner

Gets whether the current user is the guild's owner.

```csharp
[JsonProperty("owner", NullValueHandling = NullValueHandling.Ignore)]
public bool IsOwner { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordGuild_IsUnavailable"></a>IsUnavailable

Gets whether this guild is unavailable.

```csharp
[JsonProperty("unavailable", NullValueHandling = NullValueHandling.Ignore)]
public bool IsUnavailable { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordGuild_JoinedAt"></a>JoinedAt

Gets this guild's join date.

```csharp
[JsonProperty("joined_at", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset JoinedAt { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordGuild_MaxMembers"></a>MaxMembers

Gets the maximum amount of members allowed for this guild.

```csharp
[JsonProperty("max_members")]
public int? MaxMembers { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordGuild_MaxPresences"></a>MaxPresences

Gets the maximum amount of presences allowed for this guild.

```csharp
[JsonProperty("max_presences")]
public int? MaxPresences { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordGuild_MaxVideoChannelUsers"></a>MaxVideoChannelUsers

Gets the maximum amount of users allowed per video channel.

```csharp
[JsonProperty("max_video_channel_users", NullValueHandling = NullValueHandling.Ignore)]
public int? MaxVideoChannelUsers { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordGuild_MemberCount"></a>MemberCount

Gets the total number of members in this guild.

```csharp
[JsonProperty("member_count", NullValueHandling = NullValueHandling.Ignore)]
public int MemberCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_Entities_DiscordGuild_Members"></a>Members

Gets a dictionary of all the members that belong to this guild. The dictionary's key is the member ID.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordMember> Members { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_MfaLevel"></a>MfaLevel

Gets the required multi-factor authentication level for this guild.

```csharp
[JsonProperty("mfa_level", NullValueHandling = NullValueHandling.Ignore)]
public MfaLevel MfaLevel { get; }
```

#### Property Value

[MfaLevel](DSharpPlus.Entities.MfaLevel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_Name"></a>Name

Gets the guild's name.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_NsfwLevel"></a>NsfwLevel

Gets the guild's nsfw level.

```csharp
[JsonProperty("nsfw_level")]
public NsfwLevel NsfwLevel { get; }
```

#### Property Value

[NsfwLevel](DSharpPlus.NsfwLevel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_OrderedChannels"></a>OrderedChannels

Gets channels ordered in a manner in which they'd be ordered in the UI of the discord client.

```csharp
[JsonIgnore]
public IEnumerable<DiscordChannel> OrderedChannels { get; }
```

#### Property Value

[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_Owner"></a>Owner

Gets the guild's owner.

```csharp
[JsonIgnore]
public DiscordMember Owner { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_Entities_DiscordGuild_OwnerId"></a>OwnerId

Gets the ID of the guild's owner.

```csharp
[JsonProperty("owner_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong OwnerId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordGuild_Permissions"></a>Permissions

Gets permissions for the user in the guild (does not include channel overrides)

```csharp
[JsonProperty("permissions", NullValueHandling = NullValueHandling.Ignore)]
public Permissions? Permissions { get; set; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)?

### <a id="DSharpPlus_Entities_DiscordGuild_PreferredLocale"></a>PreferredLocale

Gets the preferred locale of this guild.
<p>This is used for server discovery and notices from Discord. Defaults to en-US.</p>

```csharp
[JsonProperty("preferred_locale", NullValueHandling = NullValueHandling.Ignore)]
public string PreferredLocale { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_PremiumProgressBarEnabled"></a>PremiumProgressBarEnabled

Whether the guild has the boost progress bar enabled.

```csharp
[JsonProperty("premium_progress_bar_enabled", NullValueHandling = NullValueHandling.Ignore)]
public bool PremiumProgressBarEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordGuild_PremiumSubscriptionCount"></a>PremiumSubscriptionCount

Gets the amount of members that boosted this guild.

```csharp
[JsonProperty("premium_subscription_count", NullValueHandling = NullValueHandling.Ignore)]
public int? PremiumSubscriptionCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordGuild_PremiumTier"></a>PremiumTier

Gets this guild's premium tier (Nitro boosting).

```csharp
[JsonProperty("premium_tier")]
public PremiumTier PremiumTier { get; }
```

#### Property Value

[PremiumTier](DSharpPlus.PremiumTier.md)

### <a id="DSharpPlus_Entities_DiscordGuild_PublicUpdatesChannel"></a>PublicUpdatesChannel

Gets the public updates channel (where admins and moderators receive messages from Discord) for this guild.
<p>This is only available if the guild is considered "discoverable".</p>

```csharp
[JsonIgnore]
public DiscordChannel PublicUpdatesChannel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_Roles"></a>Roles

Gets a collection of this guild's roles.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordRole> Roles { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_RulesChannel"></a>RulesChannel

Gets the rules channel for this guild.
<p>This is only available if the guild is considered "discoverable".</p>

```csharp
[JsonIgnore]
public DiscordChannel RulesChannel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_SafetyAlertsChannel"></a>SafetyAlertsChannel

Gets the guild's safety alerts channel.

```csharp
[JsonIgnore]
public DiscordChannel? SafetyAlertsChannel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)?

### <a id="DSharpPlus_Entities_DiscordGuild_ScheduledEvents"></a>ScheduledEvents

Scheduled events for this guild.

```csharp
public IReadOnlyDictionary<ulong, DiscordScheduledGuildEvent> ScheduledEvents { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_SplashHash"></a>SplashHash

Gets the guild splash's hash.

```csharp
[JsonProperty("splash", NullValueHandling = NullValueHandling.Ignore)]
public string SplashHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_SplashUrl"></a>SplashUrl

Gets the guild splash's url.

```csharp
[JsonIgnore]
public string SplashUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_StageInstances"></a>StageInstances

Gets the stage instances in this guild.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordStageInstance> StageInstances { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_Stickers"></a>Stickers

Gets a collection of this guild's stickers.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordMessageSticker> Stickers { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_SystemChannel"></a>SystemChannel

Gets the channel where system messages (such as boost and welcome messages) are sent.

```csharp
[JsonIgnore]
public DiscordChannel SystemChannel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_SystemChannelFlags"></a>SystemChannelFlags

Gets the settings for this guild's system channel.

```csharp
[JsonProperty("system_channel_flags")]
public SystemChannelFlags SystemChannelFlags { get; }
```

#### Property Value

[SystemChannelFlags](DSharpPlus.SystemChannelFlags.md)

### <a id="DSharpPlus_Entities_DiscordGuild_Threads"></a>Threads

Gets a dictionary of all the active threads associated with this guild the user has permission to view. The dictionary's key is the channel ID.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordThreadChannel> Threads { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_VanityUrlCode"></a>VanityUrlCode

Gets the vanity URL code for this guild, when applicable.

```csharp
[JsonProperty("vanity_url_code")]
public string VanityUrlCode { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordGuild_VerificationLevel"></a>VerificationLevel

Gets the guild's verification level.

```csharp
[JsonProperty("verification_level", NullValueHandling = NullValueHandling.Ignore)]
public VerificationLevel VerificationLevel { get; }
```

#### Property Value

[VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_VoiceRegion"></a>VoiceRegion

Gets the guild's voice region.

```csharp
[JsonIgnore]
public DiscordVoiceRegion VoiceRegion { get; }
```

#### Property Value

[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

### <a id="DSharpPlus_Entities_DiscordGuild_VoiceStates"></a>VoiceStates

Gets a dictionary of all the voice states for this guilds. The key for this dictionary is the ID of the user
the voice state corresponds to.

```csharp
[JsonIgnore]
public IReadOnlyDictionary<ulong, DiscordVoiceState> VoiceStates { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordVoiceState](DSharpPlus.Entities.DiscordVoiceState.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_WidgetChannel"></a>WidgetChannel

Gets the widget channel for this guild.

```csharp
[JsonIgnore]
public DiscordChannel WidgetChannel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordGuild_WidgetEnabled"></a>WidgetEnabled

Gets whether this guild's widget is enabled.

```csharp
[JsonProperty("widget_enabled", NullValueHandling = NullValueHandling.Ignore)]
public bool? WidgetEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

## Methods

### <a id="DSharpPlus_Entities_DiscordGuild_AddMemberAsync_DSharpPlus_Entities_DiscordUser_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_Boolean_System_Boolean_"></a>AddMemberAsync\(DiscordUser, string, string, IEnumerable<DiscordRole\>, bool, bool\)

Adds a new member to this guild

```csharp
public Task AddMemberAsync(DiscordUser user, string access_token, string nickname = null, IEnumerable<DiscordRole> roles = null, bool muted = false, bool deaf = false)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to add

`access\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

User's access token (OAuth2)

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

new nickname

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

new roles

`muted` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

whether this user has to be muted

`deaf` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

whether this user has to be deafened

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.CreateInstantInvite" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the <code class="paramref">user</code> or <code class="paramref">access_token</code> is not found.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_AttachUserIntegrationAsync_DSharpPlus_Entities_DiscordIntegration_"></a>AttachUserIntegrationAsync\(DiscordIntegration\)

Attaches an integration from current user to this guild.

```csharp
public Task<DiscordIntegration> AttachUserIntegrationAsync(DiscordIntegration integration)
```

#### Parameters

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to attach.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

The integration after being attached to the guild.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_BanMemberAsync_DSharpPlus_Entities_DiscordMember_System_Int32_System_String_"></a>BanMemberAsync\(DiscordMember, int, string\)

Bans a specified member from this guild.

```csharp
public Task BanMemberAsync(DiscordMember member, int delete_message_days = 0, string reason = null)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Member to ban.

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

### <a id="DSharpPlus_Entities_DiscordGuild_BanMemberAsync_System_UInt64_System_Int32_System_String_"></a>BanMemberAsync\(ulong, int, string\)

Bans a specified user by ID. This doesn't require the user to be in this guild.

```csharp
public Task BanMemberAsync(ulong user_id, int delete_message_days = 0, string reason = null)
```

#### Parameters

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the user to ban.

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

### <a id="DSharpPlus_Entities_DiscordGuild_BatchEditApplicationCommandPermissionsAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions__"></a>BatchEditApplicationCommandPermissionsAsync\(IEnumerable<DiscordGuildApplicationCommandPermissions\>\)

Batch edits permissions for a application command in this guild.

```csharp
public Task<IReadOnlyList<DiscordGuildApplicationCommandPermissions>> BatchEditApplicationCommandPermissionsAsync(IEnumerable<DiscordGuildApplicationCommandPermissions> permissions)
```

#### Parameters

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The list of permissions to use.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>\>

A list of edited permissions.

### <a id="DSharpPlus_Entities_DiscordGuild_BulkOverwriteApplicationCommandsAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommand__"></a>BulkOverwriteApplicationCommandsAsync\(IEnumerable<DiscordApplicationCommand\>\)

Overwrites the existing application commands in this guild. New commands are automatically created and missing commands are automatically delete

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> BulkOverwriteApplicationCommandsAsync(IEnumerable<DiscordApplicationCommand> commands)
```

#### Parameters

`commands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The list of commands to overwrite with.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

The list of guild commands

### <a id="DSharpPlus_Entities_DiscordGuild_CancelEventAsync_DSharpPlus_Entities_DiscordScheduledGuildEvent_"></a>CancelEventAsync\(DiscordScheduledGuildEvent\)

Cancels an event. The event must be scheduled for it to be cancelled.

```csharp
public Task CancelEventAsync(DiscordScheduledGuildEvent guildEvent)
```

#### Parameters

`guildEvent` [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

The event to delete.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordGuild_CreateApplicationCommandAsync_DSharpPlus_Entities_DiscordApplicationCommand_"></a>CreateApplicationCommandAsync\(DiscordApplicationCommand\)

Creates or overwrites a application command in this guild.

```csharp
public Task<DiscordApplicationCommand> CreateApplicationCommandAsync(DiscordApplicationCommand command)
```

#### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to create.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The created command.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateAutoModerationRuleAsync_System_String_DSharpPlus_Enums_RuleEventType_DSharpPlus_Enums_RuleTriggerType_DSharpPlus_Entities_DiscordRuleTriggerMetadata_System_Collections_Generic_IReadOnlyList_DSharpPlus_Entities_DiscordAutoModerationAction__DSharpPlus_Entities_Optional_System_Boolean__DSharpPlus_Entities_Optional_System_Collections_Generic_IReadOnlyList_DSharpPlus_Entities_DiscordRole___DSharpPlus_Entities_Optional_System_Collections_Generic_IReadOnlyList_DSharpPlus_Entities_DiscordChannel___System_String_"></a>CreateAutoModerationRuleAsync\(string, RuleEventType, RuleTriggerType, DiscordRuleTriggerMetadata, IReadOnlyList<DiscordAutoModerationAction\>, Optional<bool\>, Optional<IReadOnlyList<DiscordRole\>\>, Optional<IReadOnlyList<DiscordChannel\>\>, string\)

Creates an auto-moderation rule in the guild.

```csharp
public Task<DiscordAutoModerationRule> CreateAutoModerationRuleAsync(string name, RuleEventType eventType, RuleTriggerType triggerType, DiscordRuleTriggerMetadata triggerMetadata, IReadOnlyList<DiscordAutoModerationAction> actions, Optional<bool> enabled = default, Optional<IReadOnlyList<DiscordRole>> exemptRoles = default, Optional<IReadOnlyList<DiscordChannel>> exemptChannels = default, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The rule name.

`eventType` [RuleEventType](DSharpPlus.Enums.RuleEventType.md)

The event in which the rule should be triggered.

`triggerType` [RuleTriggerType](DSharpPlus.Enums.RuleTriggerType.md)

The type of content which can trigger the rule.

`triggerMetadata` [DiscordRuleTriggerMetadata](DSharpPlus.Entities.DiscordRuleTriggerMetadata.md)

Metadata used to determine whether a rule should be triggered. This argument can be skipped depending eventType value.

`actions` [IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordAutoModerationAction](DSharpPlus.Entities.DiscordAutoModerationAction.md)\>

Actions that will execute after the trigger of the rule.

`enabled` [Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether the rule is enabled or not.

`exemptRoles` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>\>

Roles that will not trigger the rule.

`exemptChannels` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>\>

Channels which will not trigger the rule.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The created rule.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateChannelAsync_System_String_DSharpPlus_ChannelType_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_Optional_System_String__System_Nullable_System_Int32__System_Nullable_System_Int32__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_Int32___System_Nullable_DSharpPlus_VideoQualityMode__System_Nullable_System_Int32__System_String_System_Nullable_DSharpPlus_AutoArchiveDuration__DSharpPlus_Entities_DefaultReaction_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordForumTagBuilder__System_Nullable_DSharpPlus_DefaultSortOrder__"></a>CreateChannelAsync\(string, ChannelType, DiscordChannel, Optional<string\>, int?, int?, IEnumerable<DiscordOverwriteBuilder\>, bool?, Optional<int?\>, VideoQualityMode?, int?, string, AutoArchiveDuration?, DefaultReaction?, IEnumerable<DiscordForumTagBuilder\>, DefaultSortOrder?\)

Creates a new channel in this guild.

```csharp
public Task<DiscordChannel> CreateChannelAsync(string name, ChannelType type, DiscordChannel parent = null, Optional<string> topic = default, int? bitrate = null, int? userLimit = null, IEnumerable<DiscordOverwriteBuilder> overwrites = null, bool? nsfw = null, Optional<int?> perUserRateLimit = default, VideoQualityMode? qualityMode = null, int? position = null, string reason = null, AutoArchiveDuration? defaultAutoArchiveDuration = null, DefaultReaction? defaultReactionEmoji = null, IEnumerable<DiscordForumTagBuilder> availableTags = null, DefaultSortOrder? defaultSortOrder = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the new channel.

`type` [ChannelType](DSharpPlus.ChannelType.md)

Type of the new channel.

`parent` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Category to put this channel in.

`topic` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Topic of the channel.

`bitrate` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Bitrate of the channel. Applies to voice only.

`userLimit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Maximum number of users in the channel. Applies to voice only.

`overwrites` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

Permission overwrites for this channel.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the channel is to be flagged as not safe for work. Applies to text only.

`perUserRateLimit` [Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

Slow mode timeout for users.

`qualityMode` [VideoQualityMode](DSharpPlus.VideoQualityMode.md)?

Video quality mode of the channel. Applies to voice only.

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Sorting position of the channel.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

`defaultAutoArchiveDuration` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)?

The default duration in which threads (or posts) will archive.

`defaultReactionEmoji` [DefaultReaction](DSharpPlus.Entities.DefaultReaction.md)?

If applied to a forum, the default emoji to use for forum post reactions.

`availableTags` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)\>

The tags available for a post in this channel.

`defaultSortOrder` [DefaultSortOrder](DSharpPlus.DefaultSortOrder.md)?

The default sorting order.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

The newly-created channel.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateChannelCategoryAsync_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_System_Int32__System_String_"></a>CreateChannelCategoryAsync\(string, IEnumerable<DiscordOverwriteBuilder\>, int?, string\)

Creates a new channel category in this guild.

```csharp
public Task<DiscordChannel> CreateChannelCategoryAsync(string name, IEnumerable<DiscordOverwriteBuilder> overwrites = null, int? position = null, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the new category.

`overwrites` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

Permission overwrites for this category.

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Sorting position of the channel.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

The newly-created channel category.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateEmojiAsync_System_String_System_IO_Stream_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>CreateEmojiAsync\(string, Stream, IEnumerable<DiscordRole\>, string\)

Creates a new custom emoji for this guild.

```csharp
public Task<DiscordGuildEmoji> CreateEmojiAsync(string name, Stream image, IEnumerable<DiscordRole> roles = null, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the new emoji.

`image` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Image to use as the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

Roles for which the emoji will be available. This works only if your application is whitelisted as integration.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

The newly-created emoji.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateEventAsync_System_String_System_String_System_Nullable_System_UInt64__DSharpPlus_Entities_ScheduledGuildEventType_DSharpPlus_Entities_ScheduledGuildEventPrivacyLevel_System_DateTimeOffset_System_Nullable_System_DateTimeOffset__System_String_System_String_"></a>CreateEventAsync\(string, string, ulong?, ScheduledGuildEventType, ScheduledGuildEventPrivacyLevel, DateTimeOffset, DateTimeOffset?, string, string\)

Creates a new scheduled event in this guild.

```csharp
public Task<DiscordScheduledGuildEvent> CreateEventAsync(string name, string description, ulong? channelId, ScheduledGuildEventType type, ScheduledGuildEventPrivacyLevel privacyLevel, DateTimeOffset start, DateTimeOffset? end, string location = null, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the event to create, up to 100 characters.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the event, up to 1000 characters.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

If a <xref href="DSharpPlus.Entities.ScheduledGuildEventType.StageInstance" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.Entities.ScheduledGuildEventType.VoiceChannel" data-throw-if-not-resolved="false"></xref>, the id of the channel the event will be hosted in

`type` [ScheduledGuildEventType](DSharpPlus.Entities.ScheduledGuildEventType.md)

The type of the event. <see paramref="channelId"></see> must be supplied if not an external event.

`privacyLevel` [ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)

The privacy level of thi

`start` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

When this event starts. Must be in the future, and before the end date.

`end` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

When this event ends. If supplied, must be in the future and after the end date. This is required for <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>.

`location` [string](https://learn.microsoft.com/dotnet/api/system.string)

Where this event takes place, up to 100 characters. Only applicable if the type is <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The created event.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateRoleAsync_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Entities_DiscordColor__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>CreateRoleAsync\(string, Permissions?, DiscordColor?, bool?, bool?, string, Stream, DiscordEmoji\)

Creates a new role in this guild.

```csharp
public Task<DiscordRole> CreateRoleAsync(string name = null, Permissions? permissions = null, DiscordColor? color = null, bool? hoist = null, bool? mentionable = null, string reason = null, Stream icon = null, DiscordEmoji emoji = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the role.

`permissions` [Permissions](DSharpPlus.Permissions.md)?

Permissions for the role.

`color` [DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

Color for the role.

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the role is to be hoisted.

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the role is to be mentionable.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The newly-created role.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateStickerAsync_System_String_System_String_System_String_System_IO_Stream_DSharpPlus_Entities_StickerFormat_System_String_"></a>CreateStickerAsync\(string, string, string, Stream, StickerFormat, string\)

Creates a sticker in this guild. Lottie stickers can only be created on verified and/or partnered servers.

```csharp
public Task<DiscordMessageSticker> CreateStickerAsync(string name, string description, string tags, Stream imageContents, StickerFormat format, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the sticker.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the sticker.

`tags` [string](https://learn.microsoft.com/dotnet/api/system.string)

The tags of the sticker. This must be a unicode emoji.

`imageContents` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The image content of the sticker.

`format` [StickerFormat](DSharpPlus.Entities.StickerFormat.md)

The image format of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason this sticker is being created.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_CreateTemplateAsync_System_String_System_String_"></a>CreateTemplateAsync\(string, string\)

Creates a guild template.

```csharp
public Task<DiscordGuildTemplate> CreateTemplateAsync(string name, string description = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template created.

#### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Throws when a template already exists for the guild or a null parameter is provided for the name.

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateTextChannelAsync_System_String_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_Optional_System_String__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_Int32___System_Nullable_System_Int32__System_String_"></a>CreateTextChannelAsync\(string, DiscordChannel, Optional<string\>, IEnumerable<DiscordOverwriteBuilder\>, bool?, Optional<int?\>, int?, string\)

Creates a new text channel in this guild.

```csharp
public Task<DiscordChannel> CreateTextChannelAsync(string name, DiscordChannel parent = null, Optional<string> topic = default, IEnumerable<DiscordOverwriteBuilder> overwrites = null, bool? nsfw = null, Optional<int?> perUserRateLimit = default, int? position = null, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the new channel.

`parent` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Category to put this channel in.

`topic` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Topic of the channel.

`overwrites` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

Permission overwrites for this channel.

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether the channel is to be flagged as not safe for work.

`perUserRateLimit` [Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

Slow mode timeout for users.

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Sorting position of the channel.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

The newly-created channel.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_CreateVoiceChannelAsync_System_String_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_Int32__System_Nullable_System_Int32__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_DSharpPlus_VideoQualityMode__System_Nullable_System_Int32__System_String_"></a>CreateVoiceChannelAsync\(string, DiscordChannel, int?, int?, IEnumerable<DiscordOverwriteBuilder\>, VideoQualityMode?, int?, string\)

Creates a new voice channel in this guild.

```csharp
public Task<DiscordChannel> CreateVoiceChannelAsync(string name, DiscordChannel parent = null, int? bitrate = null, int? userLimit = null, IEnumerable<DiscordOverwriteBuilder> overwrites = null, VideoQualityMode? qualityMode = null, int? position = null, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the new channel.

`parent` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Category to put this channel in.

`bitrate` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Bitrate of the channel.

`userLimit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Maximum number of users in the channel.

`overwrites` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

Permission overwrites for this channel.

`qualityMode` [VideoQualityMode](DSharpPlus.VideoQualityMode.md)?

Video quality mode of the channel.

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Sorting position of the channel.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

The newly-created channel.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteAllChannelsAsync"></a>DeleteAllChannelsAsync\(\)

<p>Deletes all channels in this guild.</p>
<p>Note that this is irreversible. Use carefully!</p>

```csharp
public Task DeleteAllChannelsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteAsync"></a>DeleteAsync\(\)

Deletes this guild. Requires the caller to be the owner of the guild.

```csharp
public Task DeleteAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client is not the owner of the guild.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteAutoModerationRuleAsync_System_UInt64_System_String_"></a>DeleteAutoModerationRuleAsync\(ulong, string\)

Deletes a auto-moderation rule by an id.

```csharp
public Task DeleteAutoModerationRuleAsync(ulong ruleId, string reason = null)
```

#### Parameters

`ruleId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The rule id.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteEmojiAsync_DSharpPlus_Entities_DiscordGuildEmoji_System_String_"></a>DeleteEmojiAsync\(DiscordGuildEmoji, string?\)

Deletes this guild's custom emoji.

```csharp
public Task DeleteEmojiAsync(DiscordGuildEmoji emoji, string? reason = null)
```

#### Parameters

`emoji` [DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)

Emoji to delete.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteEventAsync_DSharpPlus_Entities_DiscordScheduledGuildEvent_System_String_"></a>DeleteEventAsync\(DiscordScheduledGuildEvent, string\)

Deletes an exising scheduled event in this guild.

```csharp
public Task DeleteEventAsync(DiscordScheduledGuildEvent guildEvent, string reason = null)
```

#### Parameters

`guildEvent` [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteIntegrationAsync_DSharpPlus_Entities_DiscordIntegration_System_String_"></a>DeleteIntegrationAsync\(DiscordIntegration, string?\)

Removes an integration from this guild.

```csharp
public Task DeleteIntegrationAsync(DiscordIntegration integration, string? reason = null)
```

#### Parameters

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to remove.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteStickerAsync_System_UInt64_System_String_"></a>DeleteStickerAsync\(ulong, string\)

Deletes a sticker in this guild.

```csharp
public Task DeleteStickerAsync(ulong stickerId, string reason = null)
```

#### Parameters

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteStickerAsync_DSharpPlus_Entities_DiscordMessageSticker_System_String_"></a>DeleteStickerAsync\(DiscordMessageSticker, string\)

Deletes a sticker in this guild.

```csharp
public Task DeleteStickerAsync(DiscordMessageSticker sticker, string reason = null)
```

#### Parameters

`sticker` [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

Sticker to delete.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordGuild_DeleteTemplateAsync_System_String_"></a>DeleteTemplateAsync\(string\)

Deletes the template.

```csharp
public Task<DiscordGuildTemplate> DeleteTemplateAsync(string code)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template to delete.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The deleted template.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Throws when the template for the code cannot be found

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_EditApplicationCommandAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_ApplicationCommandEditModel__"></a>EditApplicationCommandAsync\(ulong, Action<ApplicationCommandEditModel\>\)

Edits a application command in this guild.

```csharp
public Task<DiscordApplicationCommand> EditApplicationCommandAsync(ulong commandId, Action<ApplicationCommandEditModel> action)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the command to edit.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)\>

Action to perform.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The edit command.

### <a id="DSharpPlus_Entities_DiscordGuild_EditApplicationCommandPermissionsAsync_DSharpPlus_Entities_DiscordApplicationCommand_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandPermission__"></a>EditApplicationCommandPermissionsAsync\(DiscordApplicationCommand, IEnumerable<DiscordApplicationCommandPermission\>\)

Edits permissions for a application command in this guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> EditApplicationCommandPermissionsAsync(DiscordApplicationCommand command, IEnumerable<DiscordApplicationCommandPermission> permissions)
```

#### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to edit permissions for.

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandPermission](DSharpPlus.Entities.DiscordApplicationCommandPermission.md)\>

The list of permissions to use.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The edited permissions.

### <a id="DSharpPlus_Entities_DiscordGuild_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordGuild_Equals_DSharpPlus_Entities_DiscordGuild_"></a>Equals\(DiscordGuild\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordGuild e)
```

#### Parameters

`e` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

<xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordGuild_GetAllMembersAsync"></a>GetAllMembersAsync\(\)

Retrieves a full list of members from Discord. This method will bypass cache.

```csharp
public Task<IReadOnlyCollection<DiscordMember>> GetAllMembersAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

A collection of all members in this guild.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandAsync_System_UInt64_"></a>GetApplicationCommandAsync\(ulong\)

Gets a application command in this guild by its id.

```csharp
public Task<DiscordApplicationCommand> GetApplicationCommandAsync(ulong commandId)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

### <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandAsync_System_String_"></a>GetApplicationCommandAsync\(string\)

Gets a application command in this guild by its name.

```csharp
public Task<DiscordApplicationCommand> GetApplicationCommandAsync(string commandName)
```

#### Parameters

`commandName` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the command to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the name.

### <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandPermissionsAsync_DSharpPlus_Entities_DiscordApplicationCommand_"></a>GetApplicationCommandPermissionsAsync\(DiscordApplicationCommand\)

Gets permissions for a application command in this guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> GetApplicationCommandPermissionsAsync(DiscordApplicationCommand command)
```

#### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to get them for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The permissions.

### <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandsAsync"></a>GetApplicationCommandsAsync\(\)

Gets all the application commands in this guild.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> GetApplicationCommandsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

A list of application commands in this guild.

### <a id="DSharpPlus_Entities_DiscordGuild_GetApplicationCommandsPermissionsAsync"></a>GetApplicationCommandsPermissionsAsync\(\)

Gets all application command permissions in this guild.

```csharp
public Task<IReadOnlyList<DiscordGuildApplicationCommandPermissions>> GetApplicationCommandsPermissionsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>\>

A list of permissions.

### <a id="DSharpPlus_Entities_DiscordGuild_GetAuditLogsAsync_System_Nullable_System_Int32__DSharpPlus_Entities_DiscordMember_System_Nullable_DSharpPlus_Entities_AuditLogs_AuditLogActionType__"></a>GetAuditLogsAsync\(int?, DiscordMember, AuditLogActionType?\)

Gets audit log entries for this guild.

```csharp
public IAsyncEnumerable<DiscordAuditLogEntry> GetAuditLogsAsync(int? limit = 100, DiscordMember byMember = null, AuditLogActionType? actionType = null)
```

#### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Maximum number of entries to fetch. Defaults to 100

`byMember` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Filter by member responsible.

`actionType` [AuditLogActionType](DSharpPlus.Entities.AuditLogs.AuditLogActionType.md)?

Filter by action type.

#### Returns

[IAsyncEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.iasyncenumerable\-1)<[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md)\>

A collection of requested audit log entries.

#### Remarks

If you set <code class="paramref">limit</code> to null, it will fetch all entries. This may take a while as it will result in multiple api calls

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ViewAuditLog" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetAutoModerationRuleAsync_System_UInt64_"></a>GetAutoModerationRuleAsync\(ulong\)

Gets an auto-moderation rule by an id.

```csharp
public Task<DiscordAutoModerationRule> GetAutoModerationRuleAsync(ulong ruleId)
```

#### Parameters

`ruleId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The rule id.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The found rule.

### <a id="DSharpPlus_Entities_DiscordGuild_GetAutoModerationRulesAsync"></a>GetAutoModerationRulesAsync\(\)

Gets all auto-moderation rules in the guild.

```csharp
public Task<IReadOnlyList<DiscordAutoModerationRule>> GetAutoModerationRulesAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>\>

All rules available in the guild.

### <a id="DSharpPlus_Entities_DiscordGuild_GetBanAsync_System_UInt64_"></a>GetBanAsync\(ulong\)

Gets a ban for a specific user.

```csharp
public Task<DiscordBan> GetBanAsync(ulong userId)
```

#### Parameters

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the user to get the ban for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>

The requested ban object.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the specified user is not banned.

### <a id="DSharpPlus_Entities_DiscordGuild_GetBanAsync_DSharpPlus_Entities_DiscordUser_"></a>GetBanAsync\(DiscordUser\)

Gets a ban for a specific user.

```csharp
public Task<DiscordBan> GetBanAsync(DiscordUser user)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to get the ban for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>

The requested ban object.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the specified user is not banned.

### <a id="DSharpPlus_Entities_DiscordGuild_GetBansAsync_System_Nullable_System_Int32__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetBansAsync\(int?, ulong?, ulong?\)

Gets the bans for this guild.

```csharp
public Task<IReadOnlyList<DiscordBan>> GetBansAsync(int? limit = null, ulong? before = null, ulong? after = null)
```

#### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The number of users to return (up to maximum 1000, default 1000).

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users before the given user id.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users after the given user id.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>\>

Collection of bans in this guild.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.BanMembers" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetChannel_System_UInt64_"></a>GetChannel\(ulong\)

Gets a channel from this guild by its ID.

```csharp
public DiscordChannel GetChannel(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the channel to get.

#### Returns

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Requested channel.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetChannelsAsync"></a>GetChannelsAsync\(\)

Gets all the channels this guild has.

```csharp
public Task<IReadOnlyList<DiscordChannel>> GetChannelsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>\>

A collection of this guild's channels.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetDefaultChannel"></a>GetDefaultChannel\(\)

<p>Gets the default channel for this guild.</p>
<p>Default channel is the first channel current member can see.</p>

```csharp
public DiscordChannel GetDefaultChannel()
```

#### Returns

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

This member's default guild.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetEmojiAsync_System_UInt64_"></a>GetEmojiAsync\(ulong\)

Gets this guild's specified custom emoji.

```csharp
public Task<DiscordGuildEmoji> GetEmojiAsync(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the emoji to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

The requested custom emoji.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetEmojisAsync"></a>GetEmojisAsync\(\)

Gets all of this guild's custom emojis.

```csharp
public Task<IReadOnlyList<DiscordGuildEmoji>> GetEmojisAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>\>

All of this guild's custom emojis.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetEventUsersAsync_DSharpPlus_Entities_DiscordScheduledGuildEvent_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetEventUsersAsync\(DiscordScheduledGuildEvent, int, ulong?, ulong?\)

Gets a list of users who are interested in this event.

```csharp
public Task<IReadOnlyList<DiscordUser>> GetEventUsersAsync(DiscordScheduledGuildEvent guildEvent, int limit = 100, ulong? after = null, ulong? before = null)
```

#### Parameters

`guildEvent` [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

The event to query users from

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How many users to fetch.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users after this id. Mutually exclusive with before

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users before this id. Mutually exclusive with after

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

### <a id="DSharpPlus_Entities_DiscordGuild_GetEventsAsync_System_Boolean_"></a>GetEventsAsync\(bool\)

Gets the currently active or scheduled events in this guild.

```csharp
public Task<IReadOnlyList<DiscordScheduledGuildEvent>> GetEventsAsync(bool withUserCounts = false)
```

#### Parameters

`withUserCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to include number of users subscribed to each event

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>\>

The active and scheduled events on the server, if any.

### <a id="DSharpPlus_Entities_DiscordGuild_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordGuild_GetIconUrl_DSharpPlus_ImageFormat_System_UInt16_"></a>GetIconUrl\(ImageFormat, ushort\)

Gets guild's icon URL, in requested format and size.

```csharp
public string GetIconUrl(ImageFormat imageFormat, ushort imageSize = 1024)
```

#### Parameters

`imageFormat` [ImageFormat](DSharpPlus.ImageFormat.md)

The image format of the icon to get.

`imageSize` [ushort](https://learn.microsoft.com/dotnet/api/system.uint16)

The maximum size of the icon. Must be a power of two, minimum 16, maximum 4096.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The URL of the guild's icon.

### <a id="DSharpPlus_Entities_DiscordGuild_GetIntegrationsAsync"></a>GetIntegrationsAsync\(\)

Gets integrations attached to this guild.

```csharp
public Task<IReadOnlyList<DiscordIntegration>> GetIntegrationsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>\>

Collection of integrations attached to this guild.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetInvite_System_String_"></a>GetInvite\(string\)

Gets an invite from this guild from an invite code.

```csharp
public DiscordInvite GetInvite(string code)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The invite code

#### Returns

[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)

An invite, or null if not in cache.

### <a id="DSharpPlus_Entities_DiscordGuild_GetInvitesAsync"></a>GetInvitesAsync\(\)

Gets all the invites created for all the channels in this guild.

```csharp
public Task<IReadOnlyList<DiscordInvite>> GetInvitesAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>\>

A collection of invites.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetMemberAsync_System_UInt64_System_Boolean_"></a>GetMemberAsync\(ulong, bool\)

Gets a member of this guild by their user ID.

```csharp
public Task<DiscordMember> GetMemberAsync(ulong userId, bool updateCache = false)
```

#### Parameters

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the member to get.

`updateCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request and update the member cache.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

The requested member.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetMembershipScreeningFormAsync"></a>GetMembershipScreeningFormAsync\(\)

Gets this guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> GetMembershipScreeningFormAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

This guild's membership screening form.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetPruneCountAsync_System_Int32_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__"></a>GetPruneCountAsync\(int, IEnumerable<DiscordRole\>\)

Estimates the number of users to be pruned.

```csharp
public Task<int> GetPruneCountAsync(int days = 7, IEnumerable<DiscordRole> includedRoles = null)
```

#### Parameters

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Minimum number of inactivity days required for users to be pruned. Defaults to 7.

`includedRoles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The roles to be included in the prune.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

Number of users that will be pruned.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.KickMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetRole_System_UInt64_"></a>GetRole\(ulong\)

Gets a role from this guild by its ID.

```csharp
public DiscordRole GetRole(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the role to get.

#### Returns

[DiscordRole](DSharpPlus.Entities.DiscordRole.md)

Requested role.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetStickerAsync_System_UInt64_"></a>GetStickerAsync\(ulong\)

Gets a sticker from this guild.

```csharp
public Task<DiscordMessageSticker> GetStickerAsync(ulong stickerId)
```

#### Parameters

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the sticker.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_GetStickersAsync"></a>GetStickersAsync\(\)

Gets a list of stickers from this guild.

```csharp
public Task<IReadOnlyList<DiscordMessageSticker>> GetStickersAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>\>

### <a id="DSharpPlus_Entities_DiscordGuild_GetTemplatesAsync"></a>GetTemplatesAsync\(\)

Gets all of this guild's templates.

```csharp
public Task<IReadOnlyList<DiscordGuildTemplate>> GetTemplatesAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>\>

All of the guild's templates.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetVanityInviteAsync"></a>GetVanityInviteAsync\(\)

Gets the vanity invite for this guild.

```csharp
public Task<DiscordInvite> GetVanityInviteAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

A partial vanity invite.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetWebhooksAsync"></a>GetWebhooksAsync\(\)

Gets all the webhooks created for all the channels in this guild.

```csharp
public Task<IReadOnlyList<DiscordWebhook>> GetWebhooksAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>\>

A collection of webhooks this guild has.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetWelcomeScreenAsync"></a>GetWelcomeScreenAsync\(\)

Gets this guild's welcome screen.

```csharp
public Task<DiscordGuildWelcomeScreen> GetWelcomeScreenAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)\>

This guild's welcome screen object.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_GetWidgetAsync"></a>GetWidgetAsync\(\)

Gets the guild's widget

```csharp
public Task<DiscordWidget> GetWidgetAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidget](DSharpPlus.Entities.DiscordWidget.md)\>

The guild's widget

### <a id="DSharpPlus_Entities_DiscordGuild_GetWidgetImage_DSharpPlus_Entities_WidgetType_"></a>GetWidgetImage\(WidgetType\)

Gets this guild's widget image.

```csharp
public string GetWidgetImage(WidgetType bannerType = WidgetType.Shield)
```

#### Parameters

`bannerType` [WidgetType](DSharpPlus.Entities.WidgetType.md)

The format of the widget.

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

The URL of the widget image.

### <a id="DSharpPlus_Entities_DiscordGuild_GetWidgetSettingsAsync"></a>GetWidgetSettingsAsync\(\)

Gets the guild's widget settings

```csharp
public Task<DiscordWidgetSettings> GetWidgetSettingsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidgetSettings](DSharpPlus.Entities.DiscordWidgetSettings.md)\>

The guild's widget settings

### <a id="DSharpPlus_Entities_DiscordGuild_LeaveAsync"></a>LeaveAsync\(\)

Leaves this guild.

```csharp
public Task LeaveAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ListActiveThreadsAsync"></a>ListActiveThreadsAsync\(\)

Gets the active and private threads for this guild.

```csharp
public Task<ThreadQueryResult> ListActiveThreadsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

A list of all the active and private threads the user can access in the server.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ListVoiceRegionsAsync"></a>ListVoiceRegionsAsync\(\)

Gets the voice regions for this guild.

```csharp
public Task<IReadOnlyList<DiscordVoiceRegion>> ListVoiceRegionsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>\>

Voice regions available for this guild.

#### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyAsync_System_Action_DSharpPlus_Net_Models_GuildEditModel__"></a>ModifyAsync\(Action<GuildEditModel\>\)

Modifies this guild.

```csharp
public Task<DiscordGuild> ModifyAsync(Action<GuildEditModel> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[GuildEditModel](DSharpPlus.Net.Models.GuildEditModel.md)\>

Action to perform on this guild..

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The modified guild object.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyAutoModerationRuleAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_AutoModerationRuleEditModel__"></a>ModifyAutoModerationRuleAsync\(ulong, Action<AutoModerationRuleEditModel\>\)

Modify an auto-moderation rule in the guild.

```csharp
public Task<DiscordAutoModerationRule> ModifyAutoModerationRuleAsync(ulong ruleId, Action<AutoModerationRuleEditModel> action)
```

#### Parameters

`ruleId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the rule that will be edited.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[AutoModerationRuleEditModel](DSharpPlus.Net.Models.AutoModerationRuleEditModel.md)\>

Action to perform on this rule.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md)\>

The modified rule.

#### Remarks

All arguments are optionals.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyEmojiAsync_DSharpPlus_Entities_DiscordGuildEmoji_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>ModifyEmojiAsync\(DiscordGuildEmoji, string, IEnumerable<DiscordRole\>, string\)

Modifies a this guild's custom emoji.

```csharp
public Task<DiscordGuildEmoji> ModifyEmojiAsync(DiscordGuildEmoji emoji, string name, IEnumerable<DiscordRole> roles = null, string reason = null)
```

#### Parameters

`emoji` [DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)

Emoji to modify.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New name for the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

Roles for which the emoji will be available. This works only if your application is whitelisted as integration.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

The modified emoji.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageEmojis" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyEventAsync_DSharpPlus_Entities_DiscordScheduledGuildEvent_System_Action_DSharpPlus_Net_Models_ScheduledGuildEventEditModel__System_String_"></a>ModifyEventAsync\(DiscordScheduledGuildEvent, Action<ScheduledGuildEventEditModel\>, string\)

Modifies an existing scheduled event in this guild.

```csharp
public Task ModifyEventAsync(DiscordScheduledGuildEvent guildEvent, Action<ScheduledGuildEventEditModel> mdl, string reason = null)
```

#### Parameters

`guildEvent` [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

The event to modify.

`mdl` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ScheduledGuildEventEditModel](DSharpPlus.Net.Models.ScheduledGuildEventEditModel.md)\>

The action to perform on this event

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason this event is being modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

The modified object

#### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyIntegrationAsync_DSharpPlus_Entities_DiscordIntegration_System_Int32_System_Int32_System_Boolean_"></a>ModifyIntegrationAsync\(DiscordIntegration, int, int, bool\)

Modifies an integration in this guild.

```csharp
public Task<DiscordIntegration> ModifyIntegrationAsync(DiscordIntegration integration, int expireBehaviour, int expireGracePeriod, bool enableEmoticons)
```

#### Parameters

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to modify.

`expireBehaviour` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of days after which the integration expires.

`expireGracePeriod` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Length of grace period which allows for renewing the integration.

`enableEmoticons` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether emotes should be synced from this integration.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

The modified integration.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyMembershipScreeningFormAsync_System_Action_DSharpPlus_Net_Models_MembershipScreeningEditModel__"></a>ModifyMembershipScreeningFormAsync\(Action<MembershipScreeningEditModel\>\)

Modifies this guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> ModifyMembershipScreeningFormAsync(Action<MembershipScreeningEditModel> action)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[MembershipScreeningEditModel](DSharpPlus.Net.Models.MembershipScreeningEditModel.md)\>

Action to perform

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

The modified screening form.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client doesn't have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission, or community is not enabled on this guild.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyRolePositionsAsync_System_Collections_Generic_IDictionary_System_Int32_DSharpPlus_Entities_DiscordRole__System_String_"></a>ModifyRolePositionsAsync\(IDictionary<int, DiscordRole\>, string\)

Batch modifies the role order in the guild.

```csharp
public Task<IReadOnlyList<DiscordRole>> ModifyRolePositionsAsync(IDictionary<int, DiscordRole> roles, string reason = null)
```

#### Parameters

`roles` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

A dictionary of guild roles indexed by their new role positions.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

An optional Audit log reason on why this action was done.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>\>

A list of all the current guild roles ordered in their new role positions.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyStickerAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_StickerEditModel__System_String_"></a>ModifyStickerAsync\(ulong, Action<StickerEditModel\>, string\)

Modifies a sticker in this guild.

```csharp
public Task<DiscordMessageSticker> ModifyStickerAsync(ulong stickerId, Action<StickerEditModel> action, string reason = null)
```

#### Parameters

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the sticker.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StickerEditModel](DSharpPlus.Net.Models.StickerEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyStickerAsync_DSharpPlus_Entities_DiscordMessageSticker_System_Action_DSharpPlus_Net_Models_StickerEditModel__System_String_"></a>ModifyStickerAsync\(DiscordMessageSticker, Action<StickerEditModel\>, string\)

Modifies a sticker in this guild.

```csharp
public Task<DiscordMessageSticker> ModifyStickerAsync(DiscordMessageSticker sticker, Action<StickerEditModel> action, string reason = null)
```

#### Parameters

`sticker` [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)

Sticker to modify.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StickerEditModel](DSharpPlus.Net.Models.StickerEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyTemplateAsync_System_String_System_String_System_String_"></a>ModifyTemplateAsync\(string, string, string\)

Modifies the template's metadata.

```csharp
public Task<DiscordGuildTemplate> ModifyTemplateAsync(string code, string name = null, string description = null)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template's code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template modified.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Throws when the template for the code cannot be found

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyWelcomeScreenAsync_System_Action_DSharpPlus_Net_Models_WelcomeScreenEditModel__System_String_"></a>ModifyWelcomeScreenAsync\(Action<WelcomeScreenEditModel\>, string\)

Modifies this guild's welcome screen.

```csharp
public Task<DiscordGuildWelcomeScreen> ModifyWelcomeScreenAsync(Action<WelcomeScreenEditModel> action, string reason = null)
```

#### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[WelcomeScreenEditModel](DSharpPlus.Net.Models.WelcomeScreenEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)\>

The modified welcome screen.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client doesn't have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission, or community is not enabled on this guild.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ModifyWidgetSettingsAsync_System_Nullable_System_Boolean__DSharpPlus_Entities_DiscordChannel_System_String_"></a>ModifyWidgetSettingsAsync\(bool?, DiscordChannel, string\)

Modifies the guild's widget settings

```csharp
public Task<DiscordWidgetSettings> ModifyWidgetSettingsAsync(bool? isEnabled = null, DiscordChannel channel = null, string reason = null)
```

#### Parameters

`isEnabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

If the widget is enabled or not

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Widget channel

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason the widget settings were modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidgetSettings](DSharpPlus.Entities.DiscordWidgetSettings.md)\>

The newly modified widget settings

### <a id="DSharpPlus_Entities_DiscordGuild_PruneAsync_System_Int32_System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>PruneAsync\(int, bool, IEnumerable<DiscordRole\>, string\)

Prunes inactive users from this guild.

```csharp
public Task<int?> PruneAsync(int days = 7, bool computePruneCount = true, IEnumerable<DiscordRole> includedRoles = null, string reason = null)
```

#### Parameters

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Minimum number of inactivity days required for users to be pruned. Defaults to 7.

`computePruneCount` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to return the prune count after this method completes. This is discouraged for larger guilds.

`includedRoles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The roles to be included in the prune.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

Number of users pruned.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_RequestMembersAsync_System_String_System_Int32_System_Nullable_System_Boolean__System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>RequestMembersAsync\(string, int, bool?, IEnumerable<ulong\>, string\)

Requests that Discord send a list of guild members based on the specified arguments. This method will fire the <xref href="DSharpPlus.DiscordClient.GuildMembersChunked" data-throw-if-not-resolved="false"></xref> event.
<p>If no arguments aside from <code class="paramref">presences</code> and <code class="paramref">nonce</code> are specified, this will request all guild members.</p>

```csharp
public Task RequestMembersAsync(string query = "", int limit = 0, bool? presences = null, IEnumerable<ulong> userIds = null, string nonce = null)
```

#### Parameters

`query` [string](https://learn.microsoft.com/dotnet/api/system.string)

Filters the returned members based on what the username starts with. Either this or <code class="paramref">userIds</code> must not be null.
    The <code class="paramref">limit</code> must also be greater than 0 if this is specified.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Total number of members to request. This must be greater than 0 if <code class="paramref">query</code> is specified.

`presences` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include the <xref href="DSharpPlus.EventArgs.GuildMembersChunkEventArgs.Presences" data-throw-if-not-resolved="false"></xref> associated with the fetched members.

`userIds` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Whether to limit the request to the specified user ids. Either this or <code class="paramref">query</code> must not be null.

`nonce` [string](https://learn.microsoft.com/dotnet/api/system.string)

The unique string to identify the response.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_Entities_DiscordGuild_SearchMembersAsync_System_String_System_Nullable_System_Int32__"></a>SearchMembersAsync\(string, int?\)

Searches the current guild for members who's display name start with the specified name.

```csharp
public Task<IReadOnlyList<DiscordMember>> SearchMembersAsync(string name, int? limit = 1)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name to search for.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The maximum amount of members to return. Max 1000. Defaults to 1.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

The members found, if any.

### <a id="DSharpPlus_Entities_DiscordGuild_StartEventAsync_DSharpPlus_Entities_DiscordScheduledGuildEvent_"></a>StartEventAsync\(DiscordScheduledGuildEvent\)

Starts a scheduled event in this guild.

```csharp
public Task StartEventAsync(DiscordScheduledGuildEvent guildEvent)
```

#### Parameters

`guildEvent` [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

The event to cancel.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

### <a id="DSharpPlus_Entities_DiscordGuild_SyncIntegrationAsync_DSharpPlus_Entities_DiscordIntegration_"></a>SyncIntegrationAsync\(DiscordIntegration\)

Forces re-synchronization of an integration for this guild.

```csharp
public Task SyncIntegrationAsync(DiscordIntegration integration)
```

#### Parameters

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to synchronize.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_SyncTemplateAsync_System_String_"></a>SyncTemplateAsync\(string\)

Syncs the template to the current guild's state.

```csharp
public Task<DiscordGuildTemplate> SyncTemplateAsync(string code)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template to sync.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template synced.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Throws when the template for the code cannot be found

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordGuild_ToString"></a>ToString\(\)

Returns a string representation of this guild.

```csharp
public override string ToString()
```

#### Returns

[string](https://learn.microsoft.com/dotnet/api/system.string)

String representation of this guild.

### <a id="DSharpPlus_Entities_DiscordGuild_UnbanMemberAsync_DSharpPlus_Entities_DiscordUser_System_String_"></a>UnbanMemberAsync\(DiscordUser, string\)

Unbans a user from this guild.

```csharp
public Task UnbanMemberAsync(DiscordUser user, string reason = null)
```

#### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to unban.

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

### <a id="DSharpPlus_Entities_DiscordGuild_UnbanMemberAsync_System_UInt64_System_String_"></a>UnbanMemberAsync\(ulong, string\)

Unbans a user by ID.

```csharp
public Task UnbanMemberAsync(ulong userId, string reason = null)
```

#### Parameters

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the user to unban.

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

### <a id="DSharpPlus_Entities_DiscordGuild_op_Equality_DSharpPlus_Entities_DiscordGuild_DSharpPlus_Entities_DiscordGuild_"></a>operator ==\(DiscordGuild, DiscordGuild\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordGuild e1, DiscordGuild e2)
```

#### Parameters

`e1` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

First member to compare.

`e2` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

Second member to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two members are equal.

### <a id="DSharpPlus_Entities_DiscordGuild_op_Inequality_DSharpPlus_Entities_DiscordGuild_DSharpPlus_Entities_DiscordGuild_"></a>operator \!=\(DiscordGuild, DiscordGuild\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordGuild e1, DiscordGuild e2)
```

#### Parameters

`e1` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

First member to compare.

`e2` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

Second member to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two members are not equal.

