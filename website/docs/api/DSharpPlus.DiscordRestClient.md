# Class DiscordRestClient

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

```csharp
public class DiscordRestClient : BaseDiscordClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordClient](DSharpPlus.BaseDiscordClient.md) ← 
[DiscordRestClient](DSharpPlus.DiscordRestClient.md)

###### Inherited Members

[BaseDiscordClient.ApiClient](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_ApiClient), 
[BaseDiscordClient.Configuration](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_Configuration), 
[BaseDiscordClient.Logger](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_Logger), 
[BaseDiscordClient.VersionString](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_VersionString), 
[BaseDiscordClient.CurrentUser](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_CurrentUser), 
[BaseDiscordClient.CurrentApplication](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_CurrentApplication), 
[BaseDiscordClient.Guilds](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_Guilds), 
[BaseDiscordClient.UserCache](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_UserCache), 
[BaseDiscordClient.VoiceRegions](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_VoiceRegions), 
[BaseDiscordClient.InternalVoiceRegions](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_InternalVoiceRegions), 
[BaseDiscordClient.GetCurrentApplicationAsync\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_GetCurrentApplicationAsync), 
[BaseDiscordClient.ListVoiceRegionsAsync\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_ListVoiceRegionsAsync), 
[BaseDiscordClient.InitializeAsync\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_InitializeAsync), 
[BaseDiscordClient.GetGatewayInfoAsync\(string\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_GetGatewayInfoAsync\_System\_String\_), 
[BaseDiscordClient.Dispose\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_Dispose)

## Constructors

### <a id="DSharpPlus_DiscordRestClient__ctor_DSharpPlus_DiscordConfiguration_"></a>DiscordRestClient\(DiscordConfiguration\)

```csharp
public DiscordRestClient(DiscordConfiguration config)
```

#### Parameters

`config` [DiscordConfiguration](DSharpPlus.DiscordConfiguration.md)

## Properties

### <a id="DSharpPlus_DiscordRestClient_Guilds"></a>Guilds

Gets the dictionary of guilds cached by this client.

```csharp
public override IReadOnlyDictionary<ulong, DiscordGuild> Guilds { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

## Methods

### <a id="DSharpPlus_DiscordRestClient_AddGuildMemberAsync_System_UInt64_System_UInt64_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_Boolean_System_Boolean_"></a>AddGuildMemberAsync\(ulong, ulong, string, string, IEnumerable<DiscordRole\>, bool, bool\)

Adds a member to a guild

```csharp
public Task<DiscordMember> AddGuildMemberAsync(ulong guild_id, ulong user_id, string access_token, string nick, IEnumerable<DiscordRole> roles, bool muted, bool deafened)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`access\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Access token

`nick` [string](https://learn.microsoft.com/dotnet/api/system.string)

User nickname

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

User roles

`muted` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this user should be muted on join

`deafened` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this user should be deafened on join

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_DiscordRestClient_AddGuildMemberRoleAsync_System_UInt64_System_UInt64_System_UInt64_System_String_"></a>AddGuildMemberRoleAsync\(ulong, ulong, ulong, string\)

Add role to guild member

```csharp
public Task AddGuildMemberRoleAsync(ulong guild_id, ulong user_id, ulong role_id, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this role gets added

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_AddThreadMemberAsync_System_UInt64_System_UInt64_"></a>AddThreadMemberAsync\(ulong, ulong\)

Adds a member to a thread.

```csharp
public Task AddThreadMemberAsync(ulong threadId, ulong userId)
```

#### Parameters

`threadId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the thread.

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the member.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_BatchEditApplicationCommandPermissionsAsync_System_UInt64_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordGuildApplicationCommandPermissions__"></a>BatchEditApplicationCommandPermissionsAsync\(ulong, IEnumerable<DiscordGuildApplicationCommandPermissions\>\)

Batch edits permissions for a application command in a guild.

```csharp
public Task<IReadOnlyList<DiscordGuildApplicationCommandPermissions>> BatchEditApplicationCommandPermissionsAsync(ulong guildId, IEnumerable<DiscordGuildApplicationCommandPermissions> permissions)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The list of permissions to use.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>\>

A list of edited permissions.

### <a id="DSharpPlus_DiscordRestClient_BeginGuildPruneAsync_System_UInt64_System_Int32_System_Boolean_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>BeginGuildPruneAsync\(ulong, int, bool, IEnumerable<ulong\>, string\)

Begins a guild prune.

```csharp
public Task<int?> BeginGuildPruneAsync(ulong guild_id, int days, bool compute_prune_count, IEnumerable<ulong> include_roles, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Days to prune for

`compute\_prune\_count` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to return the prune count after this method completes. This is discouraged for larger guilds.

`include\_roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

The roles to be included in the prune.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this guild was pruned

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

### <a id="DSharpPlus_DiscordRestClient_BulkOverwriteGlobalApplicationCommandsAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommand__"></a>BulkOverwriteGlobalApplicationCommandsAsync\(IEnumerable<DiscordApplicationCommand\>\)

Overwrites the existing global application commands. New commands are automatically created and missing commands are automatically deleted.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> BulkOverwriteGlobalApplicationCommandsAsync(IEnumerable<DiscordApplicationCommand> commands)
```

#### Parameters

`commands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The list of commands to overwrite with.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

The list of global commands.

### <a id="DSharpPlus_DiscordRestClient_BulkOverwriteGuildApplicationCommandsAsync_System_UInt64_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommand__"></a>BulkOverwriteGuildApplicationCommandsAsync\(ulong, IEnumerable<DiscordApplicationCommand\>\)

Overwrites the existing application commands in a guild. New commands are automatically created and missing commands are automatically deleted.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> BulkOverwriteGuildApplicationCommandsAsync(ulong guildId, IEnumerable<DiscordApplicationCommand> commands)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`commands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The list of commands to overwrite with.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

The list of guild commands.

### <a id="DSharpPlus_DiscordRestClient_CreateChannelInviteAsync_System_UInt64_System_Int32_System_Int32_System_Boolean_System_Boolean_System_String_System_Nullable_DSharpPlus_InviteTargetType__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>CreateChannelInviteAsync\(ulong, int, int, bool, bool, string, InviteTargetType?, ulong?, ulong?\)

Creates a channel invite

```csharp
public Task<DiscordInvite> CreateChannelInviteAsync(ulong channel_id, int max_age, int max_uses, bool temporary, bool unique, string reason, InviteTargetType? targetType = null, ulong? targetUserId = null, ulong? targetApplicationId = null)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`max\_age` [int](https://learn.microsoft.com/dotnet/api/system.int32)

For how long the invite should exist

`max\_uses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How often the invite may be used

`temporary` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this invite should be temporary

`unique` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this invite should be unique (false might return an existing invite)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why you made an invite

`targetType` [InviteTargetType](DSharpPlus.InviteTargetType.md)?

The target type of the invite, for stream and embedded application invites.

`targetUserId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target user.

`targetApplicationId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target application.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateDmAsync_System_UInt64_"></a>CreateDmAsync\(ulong\)

Creates a DM

```csharp
public Task<DiscordDmChannel> CreateDmAsync(ulong recipient_id)
```

#### Parameters

`recipient\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Recipient user ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateEmojiAsync_System_UInt64_System_String_System_IO_Stream_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>CreateEmojiAsync\(ulong, string, Stream, IEnumerable<ulong\>, string\)

Creates an emoji in a guild.

```csharp
public Task<DiscordGuildEmoji> CreateEmojiAsync(ulong guildId, string name, Stream image, IEnumerable<ulong> roles = null, string reason = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the emoji.

`image` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Image to use as the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Roles for which the emoji will be available.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateFollowupMessageAsync_System_String_DSharpPlus_Entities_DiscordFollowupMessageBuilder_"></a>CreateFollowupMessageAsync\(string, DiscordFollowupMessageBuilder\)

Creates a follow up message to an interaction.

```csharp
public Task<DiscordMessage> CreateFollowupMessageAsync(string interactionToken, DiscordFollowupMessageBuilder builder)
```

#### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction.

`builder` [DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

The webhook builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> created.

### <a id="DSharpPlus_DiscordRestClient_CreateGlobalApplicationCommandAsync_DSharpPlus_Entities_DiscordApplicationCommand_"></a>CreateGlobalApplicationCommandAsync\(DiscordApplicationCommand\)

Creates or overwrites a global application command.

```csharp
public Task<DiscordApplicationCommand> CreateGlobalApplicationCommandAsync(DiscordApplicationCommand command)
```

#### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to create.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The created command.

### <a id="DSharpPlus_DiscordRestClient_CreateGroupDmAsync_System_Collections_Generic_IEnumerable_System_String__System_Collections_Generic_IDictionary_System_UInt64_System_String__"></a>CreateGroupDmAsync\(IEnumerable<string\>, IDictionary<ulong, string\>\)

Creates a group DM

```csharp
public Task<DiscordDmChannel> CreateGroupDmAsync(IEnumerable<string> access_tokens, IDictionary<ulong, string> nicks)
```

#### Parameters

`access\_tokens` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Access tokens

`nicks` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Nicknames per user

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateGroupDmWithCurrentUserAsync_System_Collections_Generic_IEnumerable_System_String__System_Collections_Generic_IDictionary_System_UInt64_System_String__"></a>CreateGroupDmWithCurrentUserAsync\(IEnumerable<string\>, IDictionary<ulong, string\>\)

Creates a group DM with current user

```csharp
public Task<DiscordDmChannel> CreateGroupDmWithCurrentUserAsync(IEnumerable<string> access_tokens, IDictionary<ulong, string> nicks)
```

#### Parameters

`access\_tokens` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Access tokens

`nicks` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Nicknames

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateGuildApplicationCommandAsync_System_UInt64_DSharpPlus_Entities_DiscordApplicationCommand_"></a>CreateGuildApplicationCommandAsync\(ulong, DiscordApplicationCommand\)

Creates or overwrites a guild application command.

```csharp
public Task<DiscordApplicationCommand> CreateGuildApplicationCommandAsync(ulong guildId, DiscordApplicationCommand command)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to create the application command in.

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to create.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The created command.

### <a id="DSharpPlus_DiscordRestClient_CreateGuildAsync_System_String_System_String_System_String_System_Nullable_DSharpPlus_Entities_VerificationLevel__System_Nullable_DSharpPlus_Entities_DefaultMessageNotifications__System_Nullable_DSharpPlus_SystemChannelFlags__"></a>CreateGuildAsync\(string, string, string, VerificationLevel?, DefaultMessageNotifications?, SystemChannelFlags?\)

Creates a new guild

```csharp
public Task<DiscordGuild> CreateGuildAsync(string name, string region_id, string iconb64, VerificationLevel? verification_level, DefaultMessageNotifications? default_message_notifications, SystemChannelFlags? system_channel_flags)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New guild's name

`region\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

New guild's region ID

`iconb64` [string](https://learn.microsoft.com/dotnet/api/system.string)

New guild's icon (base64)

`verification\_level` [VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)?

New guild's verification level

`default\_message\_notifications` [DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)?

New guild's default message notification level

`system\_channel\_flags` [SystemChannelFlags](DSharpPlus.SystemChannelFlags.md)?

New guild's system channel flags

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateGuildBanAsync_System_UInt64_System_UInt64_System_Int32_System_String_"></a>CreateGuildBanAsync\(ulong, ulong, int, string\)

Creates guild ban

```csharp
public Task CreateGuildBanAsync(ulong guild_id, ulong user_id, int delete_message_days, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`delete\_message\_days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Days to delete messages

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this member was banned

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_CreateGuildChannelAsync_System_UInt64_System_String_DSharpPlus_ChannelType_System_Nullable_System_UInt64__DSharpPlus_Entities_Optional_System_String__System_Nullable_System_Int32__System_Nullable_System_Int32__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_Int32___System_Nullable_DSharpPlus_VideoQualityMode__System_Nullable_System_Int32__System_String_System_Nullable_DSharpPlus_AutoArchiveDuration__DSharpPlus_Entities_DefaultReaction_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordForumTagBuilder__System_Nullable_DSharpPlus_DefaultSortOrder__"></a>CreateGuildChannelAsync\(ulong, string, ChannelType, ulong?, Optional<string\>, int?, int?, IEnumerable<DiscordOverwriteBuilder\>, bool?, Optional<int?\>, VideoQualityMode?, int?, string, AutoArchiveDuration?, DefaultReaction?, IEnumerable<DiscordForumTagBuilder\>, DefaultSortOrder?\)

Creates a guild channel

```csharp
public Task<DiscordChannel> CreateGuildChannelAsync(ulong id, string name, ChannelType type, ulong? parent, Optional<string> topic, int? bitrate, int? userLimit, IEnumerable<DiscordOverwriteBuilder> overwrites, bool? nsfw, Optional<int?> perUserRateLimit, VideoQualityMode? qualityMode, int? position, string reason, AutoArchiveDuration? defaultAutoArchiveDuration = null, DefaultReaction? defaultReactionEmoji = null, IEnumerable<DiscordForumTagBuilder> availableTags = null, DefaultSortOrder? defaultSortOrder = null)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Channel name

`type` [ChannelType](DSharpPlus.ChannelType.md)

Channel type

`parent` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Channel parent ID

`topic` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Channel topic

`bitrate` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Voice channel bitrate

`userLimit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Voice channel user limit

`overwrites` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

Channel overwrites

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this channel should be marked as NSFW

`perUserRateLimit` [Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

Slow mode timeout for users.

`qualityMode` [VideoQualityMode](DSharpPlus.VideoQualityMode.md)?

Voice channel video quality mode.

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Sorting position of the channel.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this channel was created

`defaultAutoArchiveDuration` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)?

Default duration for newly created forum posts in the channel.

`defaultReactionEmoji` [DefaultReaction](DSharpPlus.Entities.DefaultReaction.md)?

Default emoji used for reacting to forum posts.

`availableTags` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)\>

Tags available for use by forum posts in the channel.

`defaultSortOrder` [DefaultSortOrder](DSharpPlus.DefaultSortOrder.md)?

Default sorting order for forum posts in the channel.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateGuildFromTemplateAsync_System_String_System_String_System_String_"></a>CreateGuildFromTemplateAsync\(string, string, string\)

Creates a guild from a template. This requires the bot to be in less than 10 guilds total.

```csharp
public Task<DiscordGuild> CreateGuildFromTemplateAsync(string code, string name, string icon)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the guild.

`icon` [string](https://learn.microsoft.com/dotnet/api/system.string)

Stream containing the icon for the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The created guild.

### <a id="DSharpPlus_DiscordRestClient_CreateGuildIntegrationAsync_System_UInt64_System_String_System_UInt64_"></a>CreateGuildIntegrationAsync\(ulong, string, ulong\)

Creates guild integration

```csharp
public Task<DiscordIntegration> CreateGuildIntegrationAsync(ulong guild_id, string type, ulong id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`type` [string](https://learn.microsoft.com/dotnet/api/system.string)

Integration type

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Integration id

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateGuildRoleAsync_System_UInt64_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_System_Int32__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>CreateGuildRoleAsync\(ulong, string, Permissions?, int?, bool?, bool?, string, Stream, DiscordEmoji\)

Creates a new role

```csharp
public Task<DiscordRole> CreateGuildRoleAsync(ulong guild_id, string name, Permissions? permissions, int? color, bool? hoist, bool? mentionable, string reason, Stream icon = null, DiscordEmoji emoji = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Role name

`permissions` [Permissions](DSharpPlus.Permissions.md)?

Role permissions

`color` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Role color

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be hoisted

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be mentionable

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this role was created

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateGuildStickerAsync_System_UInt64_System_String_System_String_System_String_System_IO_Stream_DSharpPlus_Entities_StickerFormat_System_String_"></a>CreateGuildStickerAsync\(ulong, string, string, string, Stream, StickerFormat, string\)

Creates a sticker in a guild.

```csharp
public Task<DiscordMessageSticker> CreateGuildStickerAsync(ulong guildId, string name, string description, string tags, Stream imageContents, StickerFormat format, string reason = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the sticker.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the sticker.

`tags` [string](https://learn.microsoft.com/dotnet/api/system.string)

The tags of the sticker.

`imageContents` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The image content of the sticker.

`format` [StickerFormat](DSharpPlus.Entities.StickerFormat.md)

The image format of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason this sticker is being created.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateGuildTemplateAsync_System_UInt64_System_String_System_String_"></a>CreateGuildTemplateAsync\(ulong, string, string\)

Creates a guild template.

```csharp
public Task<DiscordGuildTemplate> CreateGuildTemplateAsync(ulong guild_id, string name, string description = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template created.

### <a id="DSharpPlus_DiscordRestClient_CreateInteractionResponseAsync_System_UInt64_System_String_DSharpPlus_InteractionResponseType_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateInteractionResponseAsync\(ulong, string, InteractionResponseType, DiscordInteractionResponseBuilder\)

Creates a response to an interaction.

```csharp
public Task CreateInteractionResponseAsync(ulong interactionId, string interactionToken, InteractionResponseType type, DiscordInteractionResponseBuilder builder = null)
```

#### Parameters

`interactionId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the interaction.

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction

`type` [InteractionResponseType](DSharpPlus.InteractionResponseType.md)

The type of the response.

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data, if any, to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_System_String_"></a>CreateMessageAsync\(ulong, string\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, string content)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message (text) content

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_DSharpPlus_Entities_DiscordEmbed_"></a>CreateMessageAsync\(ulong, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, DiscordEmbed embed)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>CreateMessageAsync\(ulong, string, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, string content, DiscordEmbed embed)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message (text) content

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_DSharpPlus_Entities_DiscordMessageBuilder_"></a>CreateMessageAsync\(ulong, DiscordMessageBuilder\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, DiscordMessageBuilder builder)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The Discord Message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>CreateMessageAsync\(ulong, Action<DiscordMessageBuilder\>\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, Action<DiscordMessageBuilder> action)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The Discord Message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateReactionAsync_System_UInt64_System_UInt64_System_String_"></a>CreateReactionAsync\(ulong, ulong, string\)

Creates a new reaction

```csharp
public Task CreateReactionAsync(ulong channel_id, ulong message_id, string emoji)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

Emoji to react

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_CreateScheduledGuildEventAsync_System_UInt64_System_String_System_String_System_Nullable_System_UInt64__DSharpPlus_Entities_ScheduledGuildEventType_DSharpPlus_Entities_ScheduledGuildEventPrivacyLevel_System_DateTimeOffset_System_Nullable_System_DateTimeOffset__System_String_"></a>CreateScheduledGuildEventAsync\(ulong, string, string, ulong?, ScheduledGuildEventType, ScheduledGuildEventPrivacyLevel, DateTimeOffset, DateTimeOffset?, string\)

Creates a new scheduled guild event.

```csharp
public Task<DiscordScheduledGuildEvent> CreateScheduledGuildEventAsync(ulong guildId, string name, string description, ulong? channelId, ScheduledGuildEventType type, ScheduledGuildEventPrivacyLevel privacyLevel, DateTimeOffset start, DateTimeOffset? end, string location = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild to create an event on.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the event, up to 100 characters.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the event, up to 1000 characters.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The channel the event will take place in, if applicable.

`type` [ScheduledGuildEventType](DSharpPlus.Entities.ScheduledGuildEventType.md)

The type of event. If <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>, a end time must be specified.

`privacyLevel` [ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)

The privacy level of the event.

`start` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

When the event starts. Must be in the future and before the end date, if specified.

`end` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

When the event ends. Required for <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>

`location` [string](https://learn.microsoft.com/dotnet/api/system.string)

Where this location takes place.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The created event.

### <a id="DSharpPlus_DiscordRestClient_CreateStageInstanceAsync_System_UInt64_System_String_System_Nullable_DSharpPlus_PrivacyLevel__System_String_"></a>CreateStageInstanceAsync\(ulong, string, PrivacyLevel?, string\)

Creates a stage instance in a stage channel.

```csharp
public Task<DiscordStageInstance> CreateStageInstanceAsync(ulong channelId, string topic, PrivacyLevel? privacyLevel = null, string reason = null)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the stage channel to create it in.

`topic` [string](https://learn.microsoft.com/dotnet/api/system.string)

The topic of the stage instance.

`privacyLevel` [PrivacyLevel](DSharpPlus.PrivacyLevel.md)?

The privacy level of the stage instance.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason the stage instance was created.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The created stage instance.

### <a id="DSharpPlus_DiscordRestClient_CreateThreadAsync_System_UInt64_System_String_DSharpPlus_AutoArchiveDuration_DSharpPlus_ChannelType_System_String_"></a>CreateThreadAsync\(ulong, string, AutoArchiveDuration, ChannelType, string\)

Creates a thread.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(ulong channelId, string name, AutoArchiveDuration archiveAfter, ChannelType threadType, string reason = null)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration.

`threadType` [ChannelType](DSharpPlus.ChannelType.md)

The type of the thread.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateThreadFromMessageAsync_System_UInt64_System_UInt64_System_String_DSharpPlus_AutoArchiveDuration_System_String_"></a>CreateThreadFromMessageAsync\(ulong, ulong, string, AutoArchiveDuration, string\)

Creates a thread from a message.

```csharp
public Task<DiscordThreadChannel> CreateThreadFromMessageAsync(ulong channelId, ulong messageId, string name, AutoArchiveDuration archiveAfter, string reason = null)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateWebhookAsync_System_UInt64_System_String_System_String_System_String_"></a>CreateWebhookAsync\(ulong, string, string, string\)

Creates a new webhook

```csharp
public Task<DiscordWebhook> CreateWebhookAsync(ulong channel_id, string name, string base64_avatar, string reason)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook name

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook avatar (base64)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was created

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_CreateWebhookAsync_System_UInt64_System_String_System_IO_Stream_System_String_"></a>CreateWebhookAsync\(ulong, string, Stream, string\)

Creates a new webhook

```csharp
public Task<DiscordWebhook> CreateWebhookAsync(ulong channel_id, string name, Stream avatar = null, string reason = null)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook name

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

Webhook avatar

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was created

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_CrosspostMessageAsync_System_UInt64_System_UInt64_"></a>CrosspostMessageAsync\(ulong, ulong\)

Publishes a message in a news channel to following channels

```csharp
public Task<DiscordMessage> CrosspostMessageAsync(ulong channel_id, ulong message_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the news channel the message to crosspost belongs to

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the message to crosspost

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> and/or <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref>

### <a id="DSharpPlus_DiscordRestClient_DeleteAllReactionsAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteAllReactionsAsync\(ulong, ulong, string\)

Deletes all reactions from a message

```csharp
public Task DeleteAllReactionsAsync(ulong channel_id, ulong message_id, string reason)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why all reactions were removed

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteChannelAsync_System_UInt64_System_String_"></a>DeleteChannelAsync\(ulong, string\)

Deletes a channel

```csharp
public Task DeleteChannelAsync(ulong id, string reason)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this channel was deleted

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteChannelPermissionAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteChannelPermissionAsync\(ulong, ulong, string\)

Deletes channel overwrite

```csharp
public Task DeleteChannelPermissionAsync(ulong channel_id, ulong overwrite_id, string reason)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`overwrite\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Overwrite ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason it was deleted

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteFollowupMessageAsync_System_String_System_UInt64_"></a>DeleteFollowupMessageAsync\(string, ulong\)

Deletes a follow up message.

```csharp
public Task DeleteFollowupMessageAsync(string interactionToken, ulong messageId)
```

#### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the follow up message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGlobalApplicationCommandAsync_System_UInt64_"></a>DeleteGlobalApplicationCommandAsync\(ulong\)

Deletes a global application command.

```csharp
public Task DeleteGlobalApplicationCommandAsync(ulong commandId)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to delete.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGuildApplicationCommandAsync_System_UInt64_System_UInt64_"></a>DeleteGuildApplicationCommandAsync\(ulong, ulong\)

Deletes a application command in a guild.

```csharp
public Task DeleteGuildApplicationCommandAsync(ulong guildId, ulong commandId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to delete the application command in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGuildAsync_System_UInt64_"></a>DeleteGuildAsync\(ulong\)

Deletes a guild

```csharp
public Task DeleteGuildAsync(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGuildEmojiAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteGuildEmojiAsync\(ulong, ulong, string\)

Deletes a guild's emoji.

```csharp
public Task DeleteGuildEmojiAsync(ulong guildId, ulong emojiId, string reason = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`emojiId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the emoji.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGuildIntegrationAsync_System_UInt64_DSharpPlus_Entities_DiscordIntegration_System_String_"></a>DeleteGuildIntegrationAsync\(ulong, DiscordIntegration, string\)

Removes a guild integration

```csharp
public Task DeleteGuildIntegrationAsync(ulong guild_id, DiscordIntegration integration, string reason = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to remove

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this integration was removed

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGuildRoleAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteGuildRoleAsync\(ulong, ulong, string\)

Deletes a role

```csharp
public Task DeleteGuildRoleAsync(ulong guild_id, ulong role_id, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this role was deleted

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGuildStickerAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteGuildStickerAsync\(ulong, ulong, string\)

Deletes a sticker in a guild.

```csharp
public Task DeleteGuildStickerAsync(ulong guildId, ulong stickerId, string reason = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteGuildTemplateAsync_System_UInt64_System_String_"></a>DeleteGuildTemplateAsync\(ulong, string\)

Deletes the template.

```csharp
public Task<DiscordGuildTemplate> DeleteGuildTemplateAsync(ulong guild_id, string code)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template to delete.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The deleted template.

### <a id="DSharpPlus_DiscordRestClient_DeleteInviteAsync_System_String_System_String_"></a>DeleteInviteAsync\(string, string\)

Removes an invite

```csharp
public Task<DiscordInvite> DeleteInviteAsync(string invite_code, string reason)
```

#### Parameters

`invite\_code` [string](https://learn.microsoft.com/dotnet/api/system.string)

Invite code

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this invite was removed

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

### <a id="DSharpPlus_DiscordRestClient_DeleteMessageAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteMessageAsync\(ulong, ulong, string\)

Deletes a message

```csharp
public Task DeleteMessageAsync(ulong channel_id, ulong message_id, string reason)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why this message was deleted

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteMessagesAsync_System_UInt64_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>DeleteMessagesAsync\(ulong, IEnumerable<ulong\>, string\)

Deletes multiple messages

```csharp
public Task DeleteMessagesAsync(ulong channel_id, IEnumerable<ulong> message_ids, string reason)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_ids` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Message IDs

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason these messages were deleted

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteOriginalInteractionResponseAsync_System_String_"></a>DeleteOriginalInteractionResponseAsync\(string\)

Deletes the original interaction response.
<param name="interactionToken">The token of the interaction.</param>

```csharp
public Task DeleteOriginalInteractionResponseAsync(string interactionToken)
```

#### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteOwnReactionAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteOwnReactionAsync\(ulong, ulong, string\)

Deletes own reaction

```csharp
public Task DeleteOwnReactionAsync(ulong channel_id, ulong message_id, string emoji)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

Emoji to remove from reaction

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteReactionsEmojiAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteReactionsEmojiAsync\(ulong, ulong, string\)

Deletes all reactions of a specific reaction for a message.

```csharp
public Task DeleteReactionsEmojiAsync(ulong channelid, ulong messageId, string emoji)
```

#### Parameters

`channelid` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message.

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

The emoji to clear.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteScheduledGuildEventAsync_System_UInt64_System_UInt64_"></a>DeleteScheduledGuildEventAsync\(ulong, ulong\)

Delete a scheduled guild event.

```csharp
public Task DeleteScheduledGuildEventAsync(ulong guildId, ulong eventId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID the guild the event resides on.

`eventId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the event to delete.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteStageInstanceAsync_System_UInt64_System_String_"></a>DeleteStageInstanceAsync\(ulong, string\)

Deletes a stage instance in a stage channel.

```csharp
public Task DeleteStageInstanceAsync(ulong channelId, string reason = null)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel to delete the stage instance of.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason the stage instance was deleted.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteUserReactionAsync_System_UInt64_System_UInt64_System_UInt64_System_String_System_String_"></a>DeleteUserReactionAsync\(ulong, ulong, ulong, string, string\)

Deletes someone elses reaction

```csharp
public Task DeleteUserReactionAsync(ulong channel_id, ulong message_id, ulong user_id, string emoji, string reason)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

Emoji to remove

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this reaction was removed

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteWebhookAsync_System_UInt64_System_String_"></a>DeleteWebhookAsync\(ulong, string\)

Deletes a webhook

```csharp
public Task DeleteWebhookAsync(ulong webhook_id, string reason)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this webhook was deleted

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteWebhookAsync_System_UInt64_System_String_System_String_"></a>DeleteWebhookAsync\(ulong, string, string\)

Deletes a webhook (when user is not in said guild)

```csharp
public Task DeleteWebhookAsync(ulong webhook_id, string reason, string webhook_token)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this webhook was removed

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_DeleteWebhookMessageAsync_System_UInt64_System_String_System_UInt64_"></a>DeleteWebhookMessageAsync\(ulong, string, ulong\)

Deletes a message that was created by a webhook.

```csharp
public Task DeleteWebhookMessageAsync(ulong webhook_id, string webhook_token, ulong messageId)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message to delete

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_Dispose"></a>Dispose\(\)

Disposes of this DiscordRestClient

```csharp
public override void Dispose()
```

### <a id="DSharpPlus_DiscordRestClient_EditApplicationCommandPermissionsAsync_System_UInt64_System_UInt64_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommandPermission__"></a>EditApplicationCommandPermissionsAsync\(ulong, ulong, IEnumerable<DiscordApplicationCommandPermission\>\)

Edits permissions for a application command in a guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> EditApplicationCommandPermissionsAsync(ulong guildId, ulong commandId, IEnumerable<DiscordApplicationCommandPermission> permissions)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit permissions for.

`permissions` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommandPermission](DSharpPlus.Entities.DiscordApplicationCommandPermission.md)\>

The list of permissions to use.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The edited permissions.

### <a id="DSharpPlus_DiscordRestClient_EditChannelPermissionsAsync_System_UInt64_System_UInt64_DSharpPlus_Permissions_DSharpPlus_Permissions_System_String_System_String_"></a>EditChannelPermissionsAsync\(ulong, ulong, Permissions, Permissions, string, string\)

Edits channel overwrite

```csharp
public Task EditChannelPermissionsAsync(ulong channel_id, ulong overwrite_id, Permissions allow, Permissions deny, string type, string reason)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`overwrite\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Overwrite ID

`allow` [Permissions](DSharpPlus.Permissions.md)

Permissions to allow

`deny` [Permissions](DSharpPlus.Permissions.md)

Permissions to deny

`type` [string](https://learn.microsoft.com/dotnet/api/system.string)

Overwrite type

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this overwrite was created

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_EditFollowupMessageAsync_System_String_System_UInt64_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditFollowupMessageAsync\(string, ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits a follow up message.

```csharp
public Task<DiscordMessage> EditFollowupMessageAsync(string interactionToken, ulong messageId, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the follow up message.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The webhook builder.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> edited.

### <a id="DSharpPlus_DiscordRestClient_EditGlobalApplicationCommandAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_ApplicationCommandEditModel__"></a>EditGlobalApplicationCommandAsync\(ulong, Action<ApplicationCommandEditModel\>\)

Edits a global application command.

```csharp
public Task<DiscordApplicationCommand> EditGlobalApplicationCommandAsync(ulong commandId, Action<ApplicationCommandEditModel> action)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)\>

Action to perform.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The edited command.

### <a id="DSharpPlus_DiscordRestClient_EditGuildApplicationCommandAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_ApplicationCommandEditModel__"></a>EditGuildApplicationCommandAsync\(ulong, ulong, Action<ApplicationCommandEditModel\>\)

Edits a application command in a guild.

```csharp
public Task<DiscordApplicationCommand> EditGuildApplicationCommandAsync(ulong guildId, ulong commandId, Action<ApplicationCommandEditModel> action)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the application command is in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)\>

Action to perform.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The edited command.

### <a id="DSharpPlus_DiscordRestClient_EditMessageAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_Optional_System_String__"></a>EditMessageAsync\(ulong, ulong, Optional<string\>\)

Edits a message

```csharp
public Task<DiscordMessage> EditMessageAsync(ulong channel_id, ulong message_id, Optional<string> content)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New message content

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_EditMessageAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordEmbed__"></a>EditMessageAsync\(ulong, ulong, Optional<DiscordEmbed\>\)

Edits a message

```csharp
public Task<DiscordMessage> EditMessageAsync(ulong channel_id, ulong message_id, Optional<DiscordEmbed> embed)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`embed` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

New message embed

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_EditMessageAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_DiscordMessageBuilder_System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditMessageAsync\(ulong, ulong, DiscordMessageBuilder, bool, IEnumerable<DiscordAttachment\>\)

Edits a message

```csharp
public Task<DiscordMessage> EditMessageAsync(ulong channel_id, ulong message_id, DiscordMessageBuilder builder, bool suppressEmbeds = false, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The builder of the message to edit.

`suppressEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to suppress embeds on the message.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_EditOriginalInteractionResponseAsync_System_String_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditOriginalInteractionResponseAsync\(string, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits the original interaction response.

```csharp
public Task<DiscordMessage> EditOriginalInteractionResponseAsync(string interactionToken, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The webhook builder.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> edited.

### <a id="DSharpPlus_DiscordRestClient_EditWebhookMessageAsync_System_UInt64_System_String_System_UInt64_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditWebhookMessageAsync\(ulong, string, ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits a previously-sent webhook message.

```csharp
public Task<DiscordMessage> EditWebhookMessageAsync(ulong webhook_id, string webhook_token, ulong messageId, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message to edit.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The builder of the message to edit.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The modified <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>

### <a id="DSharpPlus_DiscordRestClient_ExecuteWebhookAsync_System_UInt64_System_String_DSharpPlus_Entities_DiscordWebhookBuilder_"></a>ExecuteWebhookAsync\(ulong, string, DiscordWebhookBuilder\)

Sends a message to a webhook

```csharp
public Task<DiscordMessage> ExecuteWebhookAsync(ulong webhook_id, string webhook_token, DiscordWebhookBuilder builder)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

Webhook builder filled with data to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_FollowChannelAsync_System_UInt64_System_UInt64_"></a>FollowChannelAsync\(ulong, ulong\)

Follows a news channel

```csharp
public Task<DiscordFollowedChannel> FollowChannelAsync(ulong channel_id, ulong webhook_channel_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the channel to follow

`webhook\_channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the channel to crosspost messages to

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordFollowedChannel](DSharpPlus.Entities.DiscordFollowedChannel.md)\>

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> on the target channel

### <a id="DSharpPlus_DiscordRestClient_GetApplicationAssetsAsync_DSharpPlus_Entities_DiscordApplication_"></a>GetApplicationAssetsAsync\(DiscordApplication\)

Gets assets from an application

```csharp
public Task<IReadOnlyList<DiscordApplicationAsset>> GetApplicationAssetsAsync(DiscordApplication application)
```

#### Parameters

`application` [DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

Application to get assets from

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationAsset](DSharpPlus.Entities.DiscordApplicationAsset.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetChannelAsync_System_UInt64_"></a>GetChannelAsync\(ulong\)

Gets a channel object

```csharp
public Task<DiscordChannel> GetChannelAsync(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetChannelInvitesAsync_System_UInt64_"></a>GetChannelInvitesAsync\(ulong\)

Gets a channel's invites

```csharp
public Task<IReadOnlyList<DiscordInvite>> GetChannelInvitesAsync(ulong channel_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetChannelMessageAsync_System_UInt64_System_UInt64_"></a>GetChannelMessageAsync\(ulong, ulong\)

Gets a message from a channel

```csharp
public Task<DiscordMessage> GetChannelMessageAsync(ulong channel_id, ulong message_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetChannelMessagesAsync_System_UInt64_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetChannelMessagesAsync\(ulong, int, ulong?, ulong?, ulong?\)

Gets messages from a channel

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetChannelMessagesAsync(ulong channel_id, int limit, ulong? before, ulong? after, ulong? around)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit of messages to get

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets messages before this ID

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets messages after this ID

`around` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets messages around this ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetChannelWebhooksAsync_System_UInt64_"></a>GetChannelWebhooksAsync\(ulong\)

Gets all webhooks from a channel

```csharp
public Task<IReadOnlyList<DiscordWebhook>> GetChannelWebhooksAsync(ulong channel_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetCurrentUserAsync"></a>GetCurrentUserAsync\(\)

Gets current user object

```csharp
public Task<DiscordUser> GetCurrentUserAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetCurrentUserGuildsAsync_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetCurrentUserGuildsAsync\(int, ulong?, ulong?\)

Gets current user's guilds

```csharp
public Task<IReadOnlyList<DiscordGuild>> GetCurrentUserGuildsAsync(int limit = 100, ulong? before = null, ulong? after = null)
```

#### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit of guilds to get

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets guild before ID

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets guilds after ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetFollowupMessageAsync_System_String_System_UInt64_"></a>GetFollowupMessageAsync\(string, ulong\)

```csharp
public Task<DiscordMessage> GetFollowupMessageAsync(string interactionToken, ulong messageId)
```

#### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetGlobalApplicationCommandAsync_System_UInt64_"></a>GetGlobalApplicationCommandAsync\(ulong\)

Gets a global application command by its ID.

```csharp
public Task<DiscordApplicationCommand> GetGlobalApplicationCommandAsync(ulong commandId)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

### <a id="DSharpPlus_DiscordRestClient_GetGlobalApplicationCommandsAsync"></a>GetGlobalApplicationCommandsAsync\(\)

Gets all the global application commands for this application.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> GetGlobalApplicationCommandsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

A list of global application commands.

### <a id="DSharpPlus_DiscordRestClient_GetGuildApplicationCommandAsync_System_UInt64_System_UInt64_"></a>GetGuildApplicationCommandAsync\(ulong, ulong\)

Gets a application command in a guild by its ID.

```csharp
public Task<DiscordApplicationCommand> GetGuildApplicationCommandAsync(ulong guildId, ulong commandId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the application command is in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

### <a id="DSharpPlus_DiscordRestClient_GetGuildApplicationCommandPermissionsAsync_System_UInt64_System_UInt64_"></a>GetGuildApplicationCommandPermissionsAsync\(ulong, ulong\)

Gets permissions for a application command in a guild.

```csharp
public Task<DiscordGuildApplicationCommandPermissions> GetGuildApplicationCommandPermissionsAsync(ulong guildId, ulong commandId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get them for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>

The permissions.

### <a id="DSharpPlus_DiscordRestClient_GetGuildApplicationCommandsAsync_System_UInt64_"></a>GetGuildApplicationCommandsAsync\(ulong\)

Gets all the application commands for a guild.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> GetGuildApplicationCommandsAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to get application commands for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

A list of application commands in the guild.

### <a id="DSharpPlus_DiscordRestClient_GetGuildApplicationCommandsPermissionsAsync_System_UInt64_"></a>GetGuildApplicationCommandsPermissionsAsync\(ulong\)

Gets all application command permissions in a guild.

```csharp
public Task<IReadOnlyList<DiscordGuildApplicationCommandPermissions>> GetGuildApplicationCommandsPermissionsAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md)\>\>

A list of permissions.

### <a id="DSharpPlus_DiscordRestClient_GetGuildAsync_System_UInt64_System_Nullable_System_Boolean__"></a>GetGuildAsync\(ulong, bool?\)

Gets a guild.

```csharp
public Task<DiscordGuild> GetGuildAsync(ulong guild_id, bool? with_counts = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID to search for.

`with\_counts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include approximate presence and member counts in the returned guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildBanAsync_System_UInt64_System_UInt64_"></a>GetGuildBanAsync\(ulong, ulong\)

Gets the ban of the specified user. Requires Ban Members permission.

```csharp
public Task<DiscordBan> GetGuildBanAsync(ulong guild_id, ulong user_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to get the ban from.

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the user to get the ban for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>

A guild ban object.

### <a id="DSharpPlus_DiscordRestClient_GetGuildBansAsync_System_UInt64_System_Nullable_System_Int32__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetGuildBansAsync\(ulong, int?, ulong?, ulong?\)

Gets guild bans.

```csharp
public Task<IReadOnlyList<DiscordBan>> GetGuildBansAsync(ulong guild_id, int? limit = null, ulong? before = null, ulong? after = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to get the bans from.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The number of users to return (up to maximum 1000, default 1000).

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users before the given user ID.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users after the given user ID.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>\>

A collection of the guild's bans.

### <a id="DSharpPlus_DiscordRestClient_GetGuildChannelsAsync_System_UInt64_"></a>GetGuildChannelsAsync\(ulong\)

Gets channels from a guild

```csharp
public Task<IReadOnlyList<DiscordChannel>> GetGuildChannelsAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildEmojiAsync_System_UInt64_System_UInt64_"></a>GetGuildEmojiAsync\(ulong, ulong\)

Gets a guild emoji.

```csharp
public Task<DiscordGuildEmoji> GetGuildEmojiAsync(ulong guildId, ulong emojiId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`emojiId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the emoji.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildEmojisAsync_System_UInt64_"></a>GetGuildEmojisAsync\(ulong\)

Gets a guild's emojis.

```csharp
public Task<IReadOnlyList<DiscordGuildEmoji>> GetGuildEmojisAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildIntegrationsAsync_System_UInt64_"></a>GetGuildIntegrationsAsync\(ulong\)

Gets guild integrations

```csharp
public Task<IReadOnlyList<DiscordIntegration>> GetGuildIntegrationsAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildInvitesAsync_System_UInt64_"></a>GetGuildInvitesAsync\(ulong\)

Get a guild's invites

```csharp
public Task<IReadOnlyList<DiscordInvite>> GetGuildInvitesAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildMemberAsync_System_UInt64_System_UInt64_"></a>GetGuildMemberAsync\(ulong, ulong\)

Gets guild member

```csharp
public Task<DiscordMember> GetGuildMemberAsync(ulong guild_id, ulong member_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`member\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Member ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildMembershipScreeningFormAsync_System_UInt64_"></a>GetGuildMembershipScreeningFormAsync\(ulong\)

Gets a guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> GetGuildMembershipScreeningFormAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

The guild's membership screening form.

### <a id="DSharpPlus_DiscordRestClient_GetGuildPreviewAsync_System_UInt64_"></a>GetGuildPreviewAsync\(ulong\)

Gets a guild preview.

```csharp
public Task<DiscordGuildPreview> GetGuildPreviewAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildPreview](DSharpPlus.Entities.DiscordGuildPreview.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildPruneCountAsync_System_UInt64_System_Int32_System_Collections_Generic_IEnumerable_System_UInt64__"></a>GetGuildPruneCountAsync\(ulong, int, IEnumerable<ulong\>\)

Get a guild's prune count.

```csharp
public Task<int> GetGuildPruneCountAsync(ulong guild_id, int days, IEnumerable<ulong> include_roles)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Days to check for

`include\_roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

The roles to be included in the prune.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildRolesAsync_System_UInt64_"></a>GetGuildRolesAsync\(ulong\)

Gets roles

```csharp
public Task<IReadOnlyList<DiscordRole>> GetGuildRolesAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildStickerAsync_System_UInt64_System_UInt64_"></a>GetGuildStickerAsync\(ulong, ulong\)

Gets a sticker from a guild.

```csharp
public Task<DiscordMessageSticker> GetGuildStickerAsync(ulong guildId, ulong stickerId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildStickersAsync_System_UInt64_"></a>GetGuildStickersAsync\(ulong\)

Gets a list of stickers from a guild.

```csharp
public Task<IReadOnlyList<DiscordMessageSticker>> GetGuildStickersAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildTemplatesAsync_System_UInt64_"></a>GetGuildTemplatesAsync\(ulong\)

Gets a guild's templates.

```csharp
public Task<IReadOnlyList<DiscordGuildTemplate>> GetGuildTemplatesAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>\>

All of the guild's templates.

### <a id="DSharpPlus_DiscordRestClient_GetGuildVanityUrlAsync_System_UInt64_"></a>GetGuildVanityUrlAsync\(ulong\)

Gets a guild's vanity url

```csharp
public Task<DiscordInvite> GetGuildVanityUrlAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

The guild's vanity url.

### <a id="DSharpPlus_DiscordRestClient_GetGuildVoiceRegionsAsync_System_UInt64_"></a>GetGuildVoiceRegionsAsync\(ulong\)

Get a guild's voice region

```csharp
public Task<IReadOnlyList<DiscordVoiceRegion>> GetGuildVoiceRegionsAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildWebhooksAsync_System_UInt64_"></a>GetGuildWebhooksAsync\(ulong\)

Gets all webhooks from a guild

```csharp
public Task<IReadOnlyList<DiscordWebhook>> GetGuildWebhooksAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildWelcomeScreenAsync_System_UInt64_"></a>GetGuildWelcomeScreenAsync\(ulong\)

Gets a guild's welcome screen.

```csharp
public Task<DiscordGuildWelcomeScreen> GetGuildWelcomeScreenAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)\>

The guild's welcome screen object.

### <a id="DSharpPlus_DiscordRestClient_GetGuildWidgetAsync_System_UInt64_"></a>GetGuildWidgetAsync\(ulong\)

Gets a guild's widget

```csharp
public Task<DiscordWidget> GetGuildWidgetAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidget](DSharpPlus.Entities.DiscordWidget.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetGuildWidgetSettingsAsync_System_UInt64_"></a>GetGuildWidgetSettingsAsync\(ulong\)

Gets a guild's widget settings

```csharp
public Task<DiscordWidgetSettings> GetGuildWidgetSettingsAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidgetSettings](DSharpPlus.Entities.DiscordWidgetSettings.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetInviteAsync_System_String_System_Nullable_System_Boolean__System_Nullable_System_Boolean__"></a>GetInviteAsync\(string, bool?, bool?\)

Gets an invite.

```csharp
public Task<DiscordInvite> GetInviteAsync(string invite_code, bool? withCounts = null, bool? withExpiration = null)
```

#### Parameters

`invite\_code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The invite code.

`withCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include presence and total member counts in the returned invite.

`withExpiration` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include the expiration date in the returned invite.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetMessageAsync_System_UInt64_System_UInt64_"></a>GetMessageAsync\(ulong, ulong\)

Gets message in a channel

```csharp
public Task<DiscordMessage> GetMessageAsync(ulong channel_id, ulong message_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetOriginalInteractionResponseAsync_System_String_"></a>GetOriginalInteractionResponseAsync\(string\)

Gets the original interaction response.

```csharp
public Task<DiscordMessage> GetOriginalInteractionResponseAsync(string interactionToken)
```

#### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The original message that was sent. This <b>does not work on ephemeral messages.</b>

### <a id="DSharpPlus_DiscordRestClient_GetPinnedMessagesAsync_System_UInt64_"></a>GetPinnedMessagesAsync\(ulong\)

Gets pinned messages

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetPinnedMessagesAsync(ulong channel_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetReactionsAsync_System_UInt64_System_UInt64_System_String_System_Nullable_System_UInt64__System_Int32_"></a>GetReactionsAsync\(ulong, ulong, string, ulong?, int\)

Gets all users that reacted with a specific emoji to a message

```csharp
public Task<IReadOnlyList<DiscordUser>> GetReactionsAsync(ulong channel_id, ulong message_id, string emoji, ulong? after_id = null, int limit = 25)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

Emoji to check for

`after\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Whether to search for reactions after this message id.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The maximum amount of reactions to fetch.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetReactionsAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_DiscordEmoji_System_Nullable_System_UInt64__System_Int32_"></a>GetReactionsAsync\(ulong, ulong, DiscordEmoji, ulong?, int\)

Gets all users that reacted with a specific emoji to a message

```csharp
public Task<IReadOnlyList<DiscordUser>> GetReactionsAsync(ulong channel_id, ulong message_id, DiscordEmoji emoji, ulong? after_id = null, int limit = 25)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji to check for

`after\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Whether to search for reactions after this message id.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The maximum amount of reactions to fetch.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetScheduledGuildEventAsync_System_UInt64_System_UInt64_"></a>GetScheduledGuildEventAsync\(ulong, ulong\)

Gets a specific scheduled guild event.

```csharp
public Task<DiscordScheduledGuildEvent> GetScheduledGuildEventAsync(ulong guildId, ulong eventId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the event resides on.

`eventId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the event to get

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The requested event.

### <a id="DSharpPlus_DiscordRestClient_GetScheduledGuildEventUsersAsync_System_UInt64_System_UInt64_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetScheduledGuildEventUsersAsync\(ulong, ulong, int, ulong?, ulong?\)

Gets the users interested in the guild event.

```csharp
public Task<IReadOnlyList<DiscordUser>> GetScheduledGuildEventUsersAsync(ulong guildId, ulong eventId, int limit = 100, ulong? after = null, ulong? before = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the event resides on.

`eventId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the event.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How many users to query.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users after this ID.

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users before this ID.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

The users interested in the event.

### <a id="DSharpPlus_DiscordRestClient_GetScheduledGuildEventsAsync_System_UInt64_"></a>GetScheduledGuildEventsAsync\(ulong\)

Gets all available scheduled guild events.

```csharp
public Task<IReadOnlyList<DiscordScheduledGuildEvent>> GetScheduledGuildEventsAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to query.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>\>

All active and scheduled events.

### <a id="DSharpPlus_DiscordRestClient_GetStageInstanceAsync_System_UInt64_"></a>GetStageInstanceAsync\(ulong\)

Gets a stage instance in a stage channel.

```csharp
public Task<DiscordStageInstance> GetStageInstanceAsync(ulong channelId)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The stage instance in the channel.

### <a id="DSharpPlus_DiscordRestClient_GetStickerAsync_System_UInt64_"></a>GetStickerAsync\(ulong\)

Gets a sticker by its ID.

```csharp
public Task<DiscordMessageSticker> GetStickerAsync(ulong stickerId)
```

#### Parameters

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetStickerPacksAsync"></a>GetStickerPacksAsync\(\)

Gets a collection of sticker packs that may be used by nitro users.

```csharp
public Task<IReadOnlyList<DiscordMessageStickerPack>> GetStickerPacksAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageStickerPack](DSharpPlus.Entities.DiscordMessageStickerPack.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetTemplateAsync_System_String_"></a>GetTemplateAsync\(string\)

Gets a guild template by the code.

```csharp
public Task<DiscordGuildTemplate> GetTemplateAsync(string code)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The guild template for the code.

### <a id="DSharpPlus_DiscordRestClient_GetUserAsync_System_UInt64_"></a>GetUserAsync\(ulong\)

Gets user object

```csharp
public Task<DiscordUser> GetUserAsync(ulong user)
```

#### Parameters

`user` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetUsersConnectionsAsync"></a>GetUsersConnectionsAsync\(\)

Gets current user's connections

```csharp
public Task<IReadOnlyList<DiscordConnection>> GetUsersConnectionsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordConnection](DSharpPlus.Entities.DiscordConnection.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_GetWebhookAsync_System_UInt64_"></a>GetWebhookAsync\(ulong\)

Gets a webhook

```csharp
public Task<DiscordWebhook> GetWebhookAsync(ulong webhook_id)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_GetWebhookWithTokenAsync_System_UInt64_System_String_"></a>GetWebhookWithTokenAsync\(ulong, string\)

Gets a webhook with its token (when user is not in said guild)

```csharp
public Task<DiscordWebhook> GetWebhookWithTokenAsync(ulong webhook_id, string webhook_token)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_GroupDmAddRecipientAsync_System_UInt64_System_UInt64_System_String_System_String_"></a>GroupDmAddRecipientAsync\(ulong, ulong, string, string\)

Adds a member to a group DM

```csharp
public Task GroupDmAddRecipientAsync(ulong channel_id, ulong user_id, string access_token, string nickname)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`access\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

User's access token

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nickname for user

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_GroupDmRemoveRecipientAsync_System_UInt64_System_UInt64_"></a>GroupDmRemoveRecipientAsync\(ulong, ulong\)

Removes a member from a group DM

```csharp
public Task GroupDmRemoveRecipientAsync(ulong channel_id, ulong user_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_InitializeCacheAsync"></a>InitializeCacheAsync\(\)

Initializes cache

```csharp
public Task InitializeCacheAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_JoinGroupDmAsync_System_UInt64_System_String_"></a>JoinGroupDmAsync\(ulong, string\)

Joins a group DM

```csharp
public Task JoinGroupDmAsync(ulong channel_id, string nickname)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

DM nickname

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_JoinThreadAsync_System_UInt64_"></a>JoinThreadAsync\(ulong\)

Joins a thread.

```csharp
public Task JoinThreadAsync(ulong threadId)
```

#### Parameters

`threadId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the thread.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_LeaveGroupDmAsync_System_UInt64_"></a>LeaveGroupDmAsync\(ulong\)

Leaves a group DM

```csharp
public Task LeaveGroupDmAsync(ulong channel_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_LeaveGuildAsync_System_UInt64_"></a>LeaveGuildAsync\(ulong\)

Leaves a guild

```csharp
public Task LeaveGuildAsync(ulong guild_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_LeaveThreadAsync_System_UInt64_"></a>LeaveThreadAsync\(ulong\)

Leaves a thread.

```csharp
public Task LeaveThreadAsync(ulong threadId)
```

#### Parameters

`threadId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the thread.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ListActiveThreadAsync_System_UInt64_"></a>ListActiveThreadAsync\(ulong\)

Lists the active threads of a guild.

```csharp
public Task<ThreadQueryResult> ListActiveThreadAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

### <a id="DSharpPlus_DiscordRestClient_ListGuildMembersAsync_System_UInt64_System_Nullable_System_Int32__System_Nullable_System_UInt64__"></a>ListGuildMembersAsync\(ulong, int?, ulong?\)

Gets all guild members

```csharp
public Task<IReadOnlyList<DiscordMember>> ListGuildMembersAsync(ulong guild_id, int? limit, ulong? after)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Member download limit

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets members after this ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_ListJoinedPrivateArchivedThreadsAsync_System_UInt64_System_UInt64_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListJoinedPrivateArchivedThreadsAsync\(ulong, ulong, DateTimeOffset?, int\)

Gets the private archived threads the user has joined for a channel.

```csharp
public Task<ThreadQueryResult> ListJoinedPrivateArchivedThreadsAsync(ulong guildId, ulong channelId, DateTimeOffset? before = null, int limit = 0)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Date to filter by.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

### <a id="DSharpPlus_DiscordRestClient_ListPrivateArchivedThreadAsync_System_UInt64_System_UInt64_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListPrivateArchivedThreadAsync\(ulong, ulong, DateTimeOffset?, int\)

Gets the threads that are public and archived for a channel.

```csharp
public Task<ThreadQueryResult> ListPrivateArchivedThreadAsync(ulong guildId, ulong channelId, DateTimeOffset? before = null, int limit = 0)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Date to filter by.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

### <a id="DSharpPlus_DiscordRestClient_ListPublicArchivedThreadsAsync_System_UInt64_System_UInt64_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListPublicArchivedThreadsAsync\(ulong, ulong, DateTimeOffset?, int\)

Gets the threads that are public and archived for a channel.

```csharp
public Task<ThreadQueryResult> ListPublicArchivedThreadsAsync(ulong guildId, ulong channelId, DateTimeOffset? before = null, int limit = 0)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Date to filter by.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

### <a id="DSharpPlus_DiscordRestClient_ListThreadMembersAsync_System_UInt64_"></a>ListThreadMembersAsync\(ulong\)

Lists the members of a thread.

```csharp
public Task<IReadOnlyList<DiscordThreadChannelMember>> ListThreadMembersAsync(ulong threadId)
```

#### Parameters

`threadId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the thread.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)\>\>

### <a id="DSharpPlus_DiscordRestClient_ModifyAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_MemberEditModel__"></a>ModifyAsync\(ulong, ulong, Action<MemberEditModel\>\)

Modifies a member

```csharp
public Task ModifyAsync(ulong member_id, ulong guild_id, Action<MemberEditModel> action)
```

#### Parameters

`member\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Member ID

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[MemberEditModel](DSharpPlus.Net.Models.MemberEditModel.md)\>

Modifications

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ModifyChannelAsync_System_UInt64_System_String_System_Nullable_System_Int32__DSharpPlus_Entities_Optional_System_String__System_Nullable_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___System_Nullable_System_Int32__System_Nullable_System_Int32__DSharpPlus_Entities_Optional_System_Nullable_System_Int32___DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordVoiceRegion__System_Nullable_DSharpPlus_VideoQualityMode__DSharpPlus_Entities_Optional_DSharpPlus_ChannelType__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_String_DSharpPlus_Entities_Optional_DSharpPlus_ChannelFlags__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordForumTagBuilder__DSharpPlus_Entities_Optional_System_Nullable_DSharpPlus_AutoArchiveDuration___DSharpPlus_Entities_Optional_DSharpPlus_Entities_DefaultReaction__DSharpPlus_Entities_Optional_System_Int32__DSharpPlus_Entities_Optional_System_Nullable_DSharpPlus_DefaultSortOrder___DSharpPlus_Entities_Optional_DSharpPlus_DefaultForumLayout__"></a>ModifyChannelAsync\(ulong, string, int?, Optional<string\>, bool?, Optional<ulong?\>, int?, int?, Optional<int?\>, Optional<DiscordVoiceRegion\>, VideoQualityMode?, Optional<ChannelType\>, IEnumerable<DiscordOverwriteBuilder\>, string, Optional<ChannelFlags\>, IEnumerable<DiscordForumTagBuilder\>?, Optional<AutoArchiveDuration?\>, Optional<DefaultReaction?\>, Optional<int\>, Optional<DefaultSortOrder?\>, Optional<DefaultForumLayout\>\)

Modifies a channel

```csharp
public Task ModifyChannelAsync(ulong id, string name, int? position, Optional<string> topic, bool? nsfw, Optional<ulong?> parent, int? bitrate, int? userLimit, Optional<int?> perUserRateLimit, Optional<DiscordVoiceRegion> rtcRegion, VideoQualityMode? qualityMode, Optional<ChannelType> type, IEnumerable<DiscordOverwriteBuilder> permissionOverwrites, string reason, Optional<ChannelFlags> flags, IEnumerable<DiscordForumTagBuilder>? availableTags, Optional<AutoArchiveDuration?> defaultAutoArchiveDuration, Optional<DefaultReaction?> defaultReactionEmoji, Optional<int> defaultPerUserRatelimit, Optional<DefaultSortOrder?> defaultSortOrder, Optional<DefaultForumLayout> defaultForumLayout)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New channel name

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

New channel position

`topic` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New channel topic

`nsfw` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this channel should be marked as NSFW

`parent` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New channel parent

`bitrate` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

New voice channel bitrate

`userLimit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

New voice channel user limit

`perUserRateLimit` [Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

Slow mode timeout for users.

`rtcRegion` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>

New region override.

`qualityMode` [VideoQualityMode](DSharpPlus.VideoQualityMode.md)?

New video quality mode.

`type` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ChannelType](DSharpPlus.ChannelType.md)\>

New channel type.

`permissionOverwrites` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

New channel permission overwrites.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this channel was modified

`flags` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ChannelFlags](DSharpPlus.ChannelFlags.md)\>

Channel flags.

`availableTags` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordForumTagBuilder](DSharpPlus.Entities.DiscordForumTagBuilder.md)\>?

Tags available for use by forum posts in the channel.

`defaultAutoArchiveDuration` [Optional](DSharpPlus.Entities.Optional\-1.md)<[AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)?\>

Default duration for newly created forum posts in the channel.

`defaultReactionEmoji` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultReaction](DSharpPlus.Entities.DefaultReaction.md)?\>

Default emoji used for reacting to forum posts.

`defaultPerUserRatelimit` [Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

Default per-user ratelimit for forum posts in the channel.

`defaultSortOrder` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultSortOrder](DSharpPlus.DefaultSortOrder.md)?\>

Default sorting order for forum posts in the channel.

`defaultForumLayout` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultForumLayout](DSharpPlus.DefaultForumLayout.md)\>

Default layout for forum posts in the channel.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ModifyChannelAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_ChannelEditModel__"></a>ModifyChannelAsync\(ulong, Action<ChannelEditModel\>\)

Modifies a channel

```csharp
public Task ModifyChannelAsync(ulong channelId, Action<ChannelEditModel> action)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ChannelEditModel](DSharpPlus.Net.Models.ChannelEditModel.md)\>

Channel modifications

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ModifyCurrentMemberAsync_System_UInt64_System_String_System_String_"></a>ModifyCurrentMemberAsync\(ulong, string, string\)

Changes the current user in a guild.

```csharp
public Task ModifyCurrentMemberAsync(ulong guild_id, string nickname, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nickname to set

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Audit log reason

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ModifyCurrentUserAsync_System_String_System_String_"></a>ModifyCurrentUserAsync\(string, string\)

Modifies current user

```csharp
public Task<DiscordUser> ModifyCurrentUserAsync(string username, string base64_avatar)
```

#### Parameters

`username` [string](https://learn.microsoft.com/dotnet/api/system.string)

New username

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

New avatar (base64)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyCurrentUserAsync_System_String_System_IO_Stream_"></a>ModifyCurrentUserAsync\(string, Stream\)

Modifies current user

```csharp
public Task<DiscordUser> ModifyCurrentUserAsync(string username = null, Stream avatar = null)
```

#### Parameters

`username` [string](https://learn.microsoft.com/dotnet/api/system.string)

username

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

avatar

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyEmbedSuppressionAsync_System_UInt64_System_UInt64_System_Boolean_"></a>ModifyEmbedSuppressionAsync\(ulong, ulong, bool\)

Modifies the visibility of embeds in a message.

```csharp
public Task ModifyEmbedSuppressionAsync(ulong channel_id, ulong message_id, bool hideEmbeds)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`hideEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to hide all embeds.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildAsync_System_UInt64_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_DSharpPlus_Entities_VerificationLevel__DSharpPlus_Entities_Optional_DSharpPlus_Entities_DefaultMessageNotifications__DSharpPlus_Entities_Optional_DSharpPlus_Entities_MfaLevel__DSharpPlus_Entities_Optional_DSharpPlus_Entities_ExplicitContentFilter__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_Int32__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_UInt64__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Collections_Generic_IEnumerable_System_String___DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_DSharpPlus_SystemChannelFlags__System_String_"></a>ModifyGuildAsync\(ulong, Optional<string\>, Optional<string\>, Optional<VerificationLevel\>, Optional<DefaultMessageNotifications\>, Optional<MfaLevel\>, Optional<ExplicitContentFilter\>, Optional<ulong?\>, Optional<int\>, Optional<string\>, Optional<ulong\>, Optional<string\>, Optional<ulong?\>, Optional<string\>, Optional<string\>, Optional<string\>, Optional<IEnumerable<string\>\>, Optional<string\>, Optional<ulong?\>, Optional<ulong?\>, Optional<SystemChannelFlags\>, string\)

Modifies a guild

```csharp
public Task<DiscordGuild> ModifyGuildAsync(ulong guild_id, Optional<string> name, Optional<string> region, Optional<VerificationLevel> verification_level, Optional<DefaultMessageNotifications> default_message_notifications, Optional<MfaLevel> mfa_level, Optional<ExplicitContentFilter> explicit_content_filter, Optional<ulong?> afk_channel_id, Optional<int> afk_timeout, Optional<string> iconb64, Optional<ulong> owner_id, Optional<string> splashb64, Optional<ulong?> systemChannelId, Optional<string> banner, Optional<string> description, Optional<string> discorverySplash, Optional<IEnumerable<string>> features, Optional<string> preferredLocale, Optional<ulong?> publicUpdatesChannelId, Optional<ulong?> rulesChannelId, Optional<SystemChannelFlags> systemChannelFlags, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`name` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild Name

`region` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild voice region

`verification\_level` [Optional](DSharpPlus.Entities.Optional\-1.md)<[VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)\>

New guild verification level

`default\_message\_notifications` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)\>

New guild default message notification level

`mfa\_level` [Optional](DSharpPlus.Entities.Optional\-1.md)<[MfaLevel](DSharpPlus.Entities.MfaLevel.md)\>

New guild MFA level

`explicit\_content\_filter` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ExplicitContentFilter](DSharpPlus.Entities.ExplicitContentFilter.md)\>

New guild explicit content filter level

`afk\_channel\_id` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New guild AFK channel ID

`afk\_timeout` [Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

New guild AFK timeout in seconds

`iconb64` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild icon (base64)

`owner\_id` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

New guild owner ID

`splashb64` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild splash (base64)

`systemChannelId` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New guild system channel ID

`banner` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild banner

`description` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild description

`discorverySplash` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild Discovery splash

`features` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

List of new <a href="https://discord.com/developers/docs/resources/guild#guild-object-guild-features">guild features</a>

`preferredLocale` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New preferred locale

`publicUpdatesChannelId` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New updates channel ID

`rulesChannelId` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New rules channel ID

`systemChannelFlags` [Optional](DSharpPlus.Entities.Optional\-1.md)<[SystemChannelFlags](DSharpPlus.SystemChannelFlags.md)\>

New system channel flags

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Modify reason

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_GuildEditModel__"></a>ModifyGuildAsync\(ulong, Action<GuildEditModel\>\)

Modifies a guild

```csharp
public Task<DiscordGuild> ModifyGuildAsync(ulong guild_id, Action<GuildEditModel> action)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[GuildEditModel](DSharpPlus.Net.Models.GuildEditModel.md)\>

Guild modifications

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildEmojiAsync_System_UInt64_System_UInt64_System_String_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>ModifyGuildEmojiAsync\(ulong, ulong, string, IEnumerable<ulong\>, string\)

Modifies a guild's emoji.

```csharp
public Task<DiscordGuildEmoji> ModifyGuildEmojiAsync(ulong guildId, ulong emojiId, string name, IEnumerable<ulong> roles = null, string reason = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`emojiId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the emoji.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New name of the emoji.

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Roles for which the emoji will be available.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildIntegrationAsync_System_UInt64_System_UInt64_System_Int32_System_Int32_System_Boolean_"></a>ModifyGuildIntegrationAsync\(ulong, ulong, int, int, bool\)

Modifies a guild integration

```csharp
public Task<DiscordIntegration> ModifyGuildIntegrationAsync(ulong guild_id, ulong integration_id, int expire_behaviour, int expire_grace_period, bool enable_emoticons)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`integration\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Integration ID

`expire\_behaviour` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Expiration behaviour

`expire\_grace\_period` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Expiration grace period

`enable\_emoticons` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to enable emojis for this integration

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildMemberAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Collections_Generic_IEnumerable_System_UInt64___DSharpPlus_Entities_Optional_System_Boolean__DSharpPlus_Entities_Optional_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_Nullable_System_DateTimeOffset___System_String_"></a>ModifyGuildMemberAsync\(ulong, ulong, Optional<string\>, Optional<IEnumerable<ulong\>\>, Optional<bool\>, Optional<bool\>, Optional<ulong?\>, Optional<DateTimeOffset?\>, string\)

Modifies guild member.

```csharp
public Task ModifyGuildMemberAsync(ulong guild_id, ulong user_id, Optional<string> nick, Optional<IEnumerable<ulong>> role_ids, Optional<bool> mute, Optional<bool> deaf, Optional<ulong?> voice_channel_id, Optional<DateTimeOffset?> communication_disabled_until, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`nick` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New nickname

`role\_ids` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>\>

New roles

`mute` [Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether this user should be muted

`deaf` [Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether this user should be deafened

`voice\_channel\_id` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

Voice channel to move this user to

`communication\_disabled\_until` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?\>

How long this member should be timed out for. Requires MODERATE_MEMBERS permission.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this user was modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildMembershipScreeningFormAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_MembershipScreeningEditModel__"></a>ModifyGuildMembershipScreeningFormAsync\(ulong, Action<MembershipScreeningEditModel\>\)

Modifies a guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> ModifyGuildMembershipScreeningFormAsync(ulong guild_id, Action<MembershipScreeningEditModel> action)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[MembershipScreeningEditModel](DSharpPlus.Net.Models.MembershipScreeningEditModel.md)\>

Action to perform

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

The modified screening form.

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildRoleAsync_System_UInt64_System_UInt64_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Entities_DiscordColor__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>ModifyGuildRoleAsync\(ulong, ulong, string, Permissions?, DiscordColor?, bool?, bool?, string, Stream, DiscordEmoji\)

Modifies a role

```csharp
public Task<DiscordRole> ModifyGuildRoleAsync(ulong guild_id, ulong role_id, string name, Permissions? permissions, DiscordColor? color, bool? hoist, bool? mentionable, string reason, Stream icon, DiscordEmoji emoji)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New role name

`permissions` [Permissions](DSharpPlus.Permissions.md)?

New role permissions

`color` [DiscordColor](DSharpPlus.Entities.DiscordColor.md)?

New role color

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be hoisted

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be mentionable

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why this role was modified

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildRoleAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_RoleEditModel__"></a>ModifyGuildRoleAsync\(ulong, ulong, Action<RoleEditModel\>\)

Modifies a role

```csharp
public Task ModifyGuildRoleAsync(ulong role_id, ulong guild_id, Action<RoleEditModel> action)
```

#### Parameters

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[RoleEditModel](DSharpPlus.Net.Models.RoleEditModel.md)\>

Modifications

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildStickerAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_StickerEditModel__System_String_"></a>ModifyGuildStickerAsync\(ulong, ulong, Action<StickerEditModel\>, string\)

Modifies a sticker in a guild.

```csharp
public Task<DiscordMessageSticker> ModifyGuildStickerAsync(ulong guildId, ulong stickerId, Action<StickerEditModel> action, string reason = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StickerEditModel](DSharpPlus.Net.Models.StickerEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildTemplateAsync_System_UInt64_System_String_System_String_System_String_"></a>ModifyGuildTemplateAsync\(ulong, string, string, string\)

Modifies the template's metadata.

```csharp
public Task<DiscordGuildTemplate> ModifyGuildTemplateAsync(ulong guild_id, string code, string name = null, string description = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template's code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template modified.

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildWelcomeScreenAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_WelcomeScreenEditModel__System_String_"></a>ModifyGuildWelcomeScreenAsync\(ulong, Action<WelcomeScreenEditModel\>, string\)

Modifies a guild's welcome screen.

```csharp
public Task<DiscordGuildWelcomeScreen> ModifyGuildWelcomeScreenAsync(ulong guildId, Action<WelcomeScreenEditModel> action, string reason = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID to modify.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[WelcomeScreenEditModel](DSharpPlus.Net.Models.WelcomeScreenEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The audit log reason for this action.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)\>

The modified welcome screen.

### <a id="DSharpPlus_DiscordRestClient_ModifyGuildWidgetSettingsAsync_System_UInt64_System_Nullable_System_Boolean__System_Nullable_System_UInt64__System_String_"></a>ModifyGuildWidgetSettingsAsync\(ulong, bool?, ulong?, string\)

Modifies a guild's widget settings

```csharp
public Task<DiscordWidgetSettings> ModifyGuildWidgetSettingsAsync(ulong guild_id, bool? enabled = null, ulong? channel_id = null, string reason = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`enabled` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

If the widget is enabled or not

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Widget channel ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason the widget settings were modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWidgetSettings](DSharpPlus.Entities.DiscordWidgetSettings.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyScheduledGuildEventAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_ScheduledGuildEventEditModel__"></a>ModifyScheduledGuildEventAsync\(ulong, ulong, Action<ScheduledGuildEventEditModel\>\)

Modify a scheduled guild event.

```csharp
public Task<DiscordScheduledGuildEvent> ModifyScheduledGuildEventAsync(ulong guildId, ulong eventId, Action<ScheduledGuildEventEditModel> mdl)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the event resides on.

`eventId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the event to modify.

`mdl` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ScheduledGuildEventEditModel](DSharpPlus.Net.Models.ScheduledGuildEventEditModel.md)\>

The action to apply to the event.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The modified event.

### <a id="DSharpPlus_DiscordRestClient_ModifyStageInstanceAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_StageInstanceEditModel__"></a>ModifyStageInstanceAsync\(ulong, Action<StageInstanceEditModel\>\)

Modifies a stage instance in a stage channel.

```csharp
public Task<DiscordStageInstance> ModifyStageInstanceAsync(ulong channelId, Action<StageInstanceEditModel> action)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel to modify the stage instance of.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StageInstanceEditModel](DSharpPlus.Net.Models.StageInstanceEditModel.md)\>

Action to perform.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The modified stage instance.

### <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_UInt64_System_String_System_String_System_String_"></a>ModifyWebhookAsync\(ulong, ulong, string, string, string\)

Modifies a webhook

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, ulong channelId, string name, string base64_avatar, string reason)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The new channel ID the webhook should be moved to.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook avatar (base64)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_UInt64_System_String_System_IO_Stream_System_String_"></a>ModifyWebhookAsync\(ulong, ulong, string, Stream, string\)

Modifies a webhook

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, ulong channelId, string name, Stream avatar, string reason)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The new channel ID the webhook should be moved to.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

New webhook avatar

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_String_System_String_System_String_System_String_"></a>ModifyWebhookAsync\(ulong, string, string, string, string\)

Modifies a webhook (when user is not in said guild)

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, string name, string base64_avatar, string webhook_token, string reason)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook avatar (base64)

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_ModifyWebhookAsync_System_UInt64_System_String_System_IO_Stream_System_String_System_String_"></a>ModifyWebhookAsync\(ulong, string, Stream, string, string\)

Modifies a webhook (when user is not in said guild)

```csharp
public Task<DiscordWebhook> ModifyWebhookAsync(ulong webhook_id, string name, Stream avatar, string webhook_token, string reason)
```

#### Parameters

`webhook\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Webhook ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New webhook name

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

New webhook avatar

`webhook\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Webhook token

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this webhook was modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

### <a id="DSharpPlus_DiscordRestClient_PinMessageAsync_System_UInt64_System_UInt64_"></a>PinMessageAsync\(ulong, ulong\)

Pins a message.

```csharp
public Task PinMessageAsync(ulong channelId, ulong messageId)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel the message is in.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_RemoveGuildBanAsync_System_UInt64_System_UInt64_System_String_"></a>RemoveGuildBanAsync\(ulong, ulong, string\)

Removes a guild ban

```csharp
public Task RemoveGuildBanAsync(ulong guild_id, ulong user_id, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User to unban

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this member was unbanned

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_RemoveGuildMemberAsync_System_UInt64_System_UInt64_System_String_"></a>RemoveGuildMemberAsync\(ulong, ulong, string\)

Removes guild member

```csharp
public Task RemoveGuildMemberAsync(ulong guild_id, ulong user_id, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why this user was removed

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_RemoveGuildMemberRoleAsync_System_UInt64_System_UInt64_System_UInt64_System_String_"></a>RemoveGuildMemberRoleAsync\(ulong, ulong, ulong, string\)

Remove role from member

```csharp
public Task RemoveGuildMemberRoleAsync(ulong guild_id, ulong user_id, ulong role_id, string reason)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this role gets removed

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_RemoveThreadMemberAsync_System_UInt64_System_UInt64_"></a>RemoveThreadMemberAsync\(ulong, ulong\)

Removes a member from a thread.

```csharp
public Task RemoveThreadMemberAsync(ulong threadId, ulong userId)
```

#### Parameters

`threadId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the thread.

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the member.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_SearchMembersAsync_System_UInt64_System_String_System_Nullable_System_Int32__"></a>SearchMembersAsync\(ulong, string, int?\)

Searches the given guild for members who's display name start with the specified name.

```csharp
public Task<IReadOnlyList<DiscordMember>> SearchMembersAsync(ulong guild_id, string name, int? limit = 1)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to search.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name to search for.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The maximum amount of members to return. Max 1000. Defaults to 1.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

The members found, if any.

### <a id="DSharpPlus_DiscordRestClient_SyncGuildIntegrationAsync_System_UInt64_System_UInt64_"></a>SyncGuildIntegrationAsync\(ulong, ulong\)

Syncs guild integration

```csharp
public Task SyncGuildIntegrationAsync(ulong guild_id, ulong integration_id)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`integration\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Integration ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_SyncGuildTemplateAsync_System_UInt64_System_String_"></a>SyncGuildTemplateAsync\(ulong, string\)

Syncs the template to the current guild's state.

```csharp
public Task<DiscordGuildTemplate> SyncGuildTemplateAsync(ulong guild_id, string code)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template to sync.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template synced.

### <a id="DSharpPlus_DiscordRestClient_TriggerTypingAsync_System_UInt64_"></a>TriggerTypingAsync\(ulong\)

Send a typing indicator to a channel

```csharp
public Task TriggerTypingAsync(ulong channel_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_UnpinMessageAsync_System_UInt64_System_UInt64_"></a>UnpinMessageAsync\(ulong, ulong\)

Unpins a message

```csharp
public Task UnpinMessageAsync(ulong channel_id, ulong message_id)
```

#### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_UpdateChannelPositionAsync_System_UInt64_System_UInt64_System_Int32_System_String_System_Nullable_System_Boolean__System_Nullable_System_UInt64__"></a>UpdateChannelPositionAsync\(ulong, ulong, int, string, bool?, ulong?\)

Updates a channel's position

```csharp
public Task UpdateChannelPositionAsync(ulong guild_id, ulong channel_id, int position, string reason, bool? lockPermissions = null, ulong? parentId = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Channel position

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this position was modified

`lockPermissions` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to sync channel permissions with the parent, if moving to a new category.

`parentId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The new parent id if the channel is to be moved to a new category.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_UpdateCurrentUserVoiceStateAsync_System_UInt64_System_UInt64_System_Nullable_System_Boolean__System_Nullable_System_DateTimeOffset__"></a>UpdateCurrentUserVoiceStateAsync\(ulong, ulong, bool?, DateTimeOffset?\)

Updates the current user's suppress state in a stage channel.

```csharp
public Task UpdateCurrentUserVoiceStateAsync(ulong guildId, ulong channelId, bool? suppress, DateTimeOffset? requestToSpeakTimestamp = null)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the suppress state.

`requestToSpeakTimestamp` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Sets the time the user requested to speak.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_UpdateRolePositionAsync_System_UInt64_System_UInt64_System_Int32_System_String_"></a>UpdateRolePositionAsync\(ulong, ulong, int, string\)

Updates a role's position

```csharp
public Task UpdateRolePositionAsync(ulong guild_id, ulong role_id, int position, string reason = null)
```

#### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Role position

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this position was modified

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordRestClient_UpdateUserVoiceStateAsync_System_UInt64_System_UInt64_System_UInt64_System_Nullable_System_Boolean__"></a>UpdateUserVoiceStateAsync\(ulong, ulong, ulong, bool?\)

Updates a member's suppress state in a stage channel.

```csharp
public Task UpdateUserVoiceStateAsync(ulong guildId, ulong userId, ulong channelId, bool? suppress)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the member.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the stage channel.

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the member's suppress state.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

