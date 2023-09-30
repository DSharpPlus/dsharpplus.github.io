# Method CreateChannelAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateChannelAsync_System_String_DSharpPlus_ChannelType_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_Optional_System_String__System_Nullable_System_Int32__System_Nullable_System_Int32__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_Int32___System_Nullable_DSharpPlus_VideoQualityMode__System_Nullable_System_Int32__System_String_System_Nullable_DSharpPlus_AutoArchiveDuration__DSharpPlus_Entities_DefaultReaction_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordForumTagBuilder__System_Nullable_DSharpPlus_DefaultSortOrder__"></a>CreateChannelAsync\(string, ChannelType, DiscordChannel, Optional<string\>, int?, int?, IEnumerable<DiscordOverwriteBuilder\>, bool?, Optional<int?\>, VideoQualityMode?, int?, string, AutoArchiveDuration?, DefaultReaction?, IEnumerable<DiscordForumTagBuilder\>, DefaultSortOrder?\)

Creates a new channel in this guild.

```csharp
public Task<DiscordChannel> CreateChannelAsync(string name, ChannelType type, DiscordChannel parent = null, Optional<string> topic = default, int? bitrate = null, int? userLimit = null, IEnumerable<DiscordOverwriteBuilder> overwrites = null, bool? nsfw = null, Optional<int?> perUserRateLimit = default, VideoQualityMode? qualityMode = null, int? position = null, string reason = null, AutoArchiveDuration? defaultAutoArchiveDuration = null, DefaultReaction? defaultReactionEmoji = null, IEnumerable<DiscordForumTagBuilder> availableTags = null, DefaultSortOrder? defaultSortOrder = null)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

The newly-created channel.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

