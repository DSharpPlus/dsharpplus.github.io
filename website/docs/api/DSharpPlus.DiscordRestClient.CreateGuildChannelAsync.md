# Method CreateGuildChannelAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildChannelAsync_System_UInt64_System_String_DSharpPlus_ChannelType_System_Nullable_System_UInt64__DSharpPlus_Entities_Optional_System_String__System_Nullable_System_Int32__System_Nullable_System_Int32__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_Int32___System_Nullable_DSharpPlus_VideoQualityMode__System_Nullable_System_Int32__System_String_System_Nullable_DSharpPlus_AutoArchiveDuration__DSharpPlus_Entities_DefaultReaction_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordForumTagBuilder__System_Nullable_DSharpPlus_DefaultSortOrder__"></a>CreateGuildChannelAsync\(ulong, string, ChannelType, ulong?, Optional<string\>, int?, int?, IEnumerable<DiscordOverwriteBuilder\>, bool?, Optional<int?\>, VideoQualityMode?, int?, string, AutoArchiveDuration?, DefaultReaction?, IEnumerable<DiscordForumTagBuilder\>, DefaultSortOrder?\)

Creates a guild channel

```csharp
public Task<DiscordChannel> CreateGuildChannelAsync(ulong id, string name, ChannelType type, ulong? parent, Optional<string> topic, int? bitrate, int? userLimit, IEnumerable<DiscordOverwriteBuilder> overwrites, bool? nsfw, Optional<int?> perUserRateLimit, VideoQualityMode? qualityMode, int? position, string reason, AutoArchiveDuration? defaultAutoArchiveDuration = null, DefaultReaction? defaultReactionEmoji = null, IEnumerable<DiscordForumTagBuilder> availableTags = null, DefaultSortOrder? defaultSortOrder = null)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

