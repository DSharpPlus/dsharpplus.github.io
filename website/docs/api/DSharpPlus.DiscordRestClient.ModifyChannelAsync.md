# Method ModifyChannelAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyChannelAsync_System_UInt64_System_String_System_Nullable_System_Int32__DSharpPlus_Entities_Optional_System_String__System_Nullable_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___System_Nullable_System_Int32__System_Nullable_System_Int32__DSharpPlus_Entities_Optional_System_Nullable_System_Int32___DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordVoiceRegion__System_Nullable_DSharpPlus_VideoQualityMode__DSharpPlus_Entities_Optional_DSharpPlus_ChannelType__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_String_DSharpPlus_Entities_Optional_DSharpPlus_ChannelFlags__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordForumTagBuilder__DSharpPlus_Entities_Optional_System_Nullable_DSharpPlus_AutoArchiveDuration___DSharpPlus_Entities_Optional_DSharpPlus_Entities_DefaultReaction__DSharpPlus_Entities_Optional_System_Int32__DSharpPlus_Entities_Optional_System_Nullable_DSharpPlus_DefaultSortOrder___DSharpPlus_Entities_Optional_DSharpPlus_DefaultForumLayout__"></a>ModifyChannelAsync\(ulong, string, int?, Optional<string\>, bool?, Optional<ulong?\>, int?, int?, Optional<int?\>, Optional<DiscordVoiceRegion\>, VideoQualityMode?, Optional<ChannelType\>, IEnumerable<DiscordOverwriteBuilder\>, string, Optional<ChannelFlags\>, IEnumerable<DiscordForumTagBuilder\>?, Optional<AutoArchiveDuration?\>, Optional<DefaultReaction?\>, Optional<int\>, Optional<DefaultSortOrder?\>, Optional<DefaultForumLayout\>\)

Modifies a channel

```csharp
public Task ModifyChannelAsync(ulong id, string name, int? position, Optional<string> topic, bool? nsfw, Optional<ulong?> parent, int? bitrate, int? userLimit, Optional<int?> perUserRateLimit, Optional<DiscordVoiceRegion> rtcRegion, VideoQualityMode? qualityMode, Optional<ChannelType> type, IEnumerable<DiscordOverwriteBuilder> permissionOverwrites, string reason, Optional<ChannelFlags> flags, IEnumerable<DiscordForumTagBuilder>? availableTags, Optional<AutoArchiveDuration?> defaultAutoArchiveDuration, Optional<DefaultReaction?> defaultReactionEmoji, Optional<int> defaultPerUserRatelimit, Optional<DefaultSortOrder?> defaultSortOrder, Optional<DefaultForumLayout> defaultForumLayout)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_DiscordRestClient_ModifyChannelAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_ChannelEditModel__"></a>ModifyChannelAsync\(ulong, Action<ChannelEditModel\>\)

Modifies a channel

```csharp
public Task ModifyChannelAsync(ulong channelId, Action<ChannelEditModel> action)
```

### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ChannelEditModel](DSharpPlus.Net.Models.ChannelEditModel.md)\>

Channel modifications

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

