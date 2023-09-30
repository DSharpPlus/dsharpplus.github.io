# Class DiscordDmChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a discord channel.

```csharp
public class DiscordDmChannel : DiscordChannel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md) ← 
[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)

###### Inherited Members

[DiscordChannel.GuildId](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GuildId), 
[DiscordChannel.ParentId](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ParentId), 
[DiscordChannel.Parent](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Parent), 
[DiscordChannel.Name](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Name), 
[DiscordChannel.Type](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Type), 
[DiscordChannel.Position](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Position), 
[DiscordChannel.IsPrivate](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_IsPrivate), 
[DiscordChannel.IsCategory](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_IsCategory), 
[DiscordChannel.IsThread](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_IsThread), 
[DiscordChannel.Guild](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Guild), 
[DiscordChannel.PermissionOverwrites](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_PermissionOverwrites), 
[DiscordChannel.Topic](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Topic), 
[DiscordChannel.LastMessageId](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_LastMessageId), 
[DiscordChannel.Bitrate](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Bitrate), 
[DiscordChannel.UserLimit](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_UserLimit), 
[DiscordChannel.PerUserRateLimit](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_PerUserRateLimit), 
[DiscordChannel.QualityMode](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_QualityMode), 
[DiscordChannel.LastPinTimestamp](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_LastPinTimestamp), 
[DiscordChannel.Mention](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Mention), 
[DiscordChannel.Children](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Children), 
[DiscordChannel.Threads](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Threads), 
[DiscordChannel.Users](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Users), 
[DiscordChannel.IsNSFW](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_IsNSFW), 
[DiscordChannel.RtcRegion](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_RtcRegion), 
[DiscordChannel.UserPermissions](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_UserPermissions), 
[DiscordChannel.SendMessageAsync\(string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_SendMessageAsync\_System\_String\_), 
[DiscordChannel.SendMessageAsync\(DiscordEmbed\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_SendMessageAsync\_DSharpPlus\_Entities\_DiscordEmbed\_), 
[DiscordChannel.SendMessageAsync\(string, DiscordEmbed\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_SendMessageAsync\_System\_String\_DSharpPlus\_Entities\_DiscordEmbed\_), 
[DiscordChannel.SendMessageAsync\(DiscordMessageBuilder\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_SendMessageAsync\_DSharpPlus\_Entities\_DiscordMessageBuilder\_), 
[DiscordChannel.SendMessageAsync\(Action<DiscordMessageBuilder\>\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_SendMessageAsync\_System\_Action\_DSharpPlus\_Entities\_DiscordMessageBuilder\_\_), 
[DiscordChannel.CreateGuildEventAsync\(string, string, ScheduledGuildEventPrivacyLevel, DateTimeOffset, DateTimeOffset?\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CreateGuildEventAsync\_System\_String\_System\_String\_DSharpPlus\_Entities\_ScheduledGuildEventPrivacyLevel\_System\_DateTimeOffset\_System\_Nullable\_System\_DateTimeOffset\_\_), 
[DiscordChannel.DeleteAsync\(string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_DeleteAsync\_System\_String\_), 
[DiscordChannel.CloneAsync\(string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CloneAsync\_System\_String\_), 
[DiscordChannel.GetMessageAsync\(ulong, bool\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetMessageAsync\_System\_UInt64\_System\_Boolean\_), 
[DiscordChannel.ModifyAsync\(Action<ChannelEditModel\>\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ModifyAsync\_System\_Action\_DSharpPlus\_Net\_Models\_ChannelEditModel\_\_), 
[DiscordChannel.ModifyPositionAsync\(int, string, bool?, ulong?\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ModifyPositionAsync\_System\_Int32\_System\_String\_System\_Nullable\_System\_Boolean\_\_System\_Nullable\_System\_UInt64\_\_), 
[DiscordChannel.GetMessagesBeforeAsync\(ulong, int\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetMessagesBeforeAsync\_System\_UInt64\_System\_Int32\_), 
[DiscordChannel.GetMessagesAfterAsync\(ulong, int\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetMessagesAfterAsync\_System\_UInt64\_System\_Int32\_), 
[DiscordChannel.GetMessagesAroundAsync\(ulong, int\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetMessagesAroundAsync\_System\_UInt64\_System\_Int32\_), 
[DiscordChannel.GetMessagesAsync\(int\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetMessagesAsync\_System\_Int32\_), 
[DiscordChannel.ListPublicArchivedThreadsAsync\(DateTimeOffset?, int\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ListPublicArchivedThreadsAsync\_System\_Nullable\_System\_DateTimeOffset\_\_System\_Int32\_), 
[DiscordChannel.ListPrivateArchivedThreadsAsync\(DateTimeOffset?, int\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ListPrivateArchivedThreadsAsync\_System\_Nullable\_System\_DateTimeOffset\_\_System\_Int32\_), 
[DiscordChannel.ListJoinedPrivateArchivedThreadsAsync\(DateTimeOffset?, int\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ListJoinedPrivateArchivedThreadsAsync\_System\_Nullable\_System\_DateTimeOffset\_\_System\_Int32\_), 
[DiscordChannel.DeleteMessagesAsync\(IEnumerable<DiscordMessage\>, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_DeleteMessagesAsync\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordMessage\_\_System\_String\_), 
[DiscordChannel.DeleteMessageAsync\(DiscordMessage, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_DeleteMessageAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_String\_), 
[DiscordChannel.GetInvitesAsync\(\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetInvitesAsync), 
[DiscordChannel.CreateInviteAsync\(int, int, bool, bool, string, InviteTargetType?, ulong?, ulong?\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CreateInviteAsync\_System\_Int32\_System\_Int32\_System\_Boolean\_System\_Boolean\_System\_String\_System\_Nullable\_DSharpPlus\_InviteTargetType\_\_System\_Nullable\_System\_UInt64\_\_System\_Nullable\_System\_UInt64\_\_), 
[DiscordChannel.AddOverwriteAsync\(DiscordMember, Permissions, Permissions, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_AddOverwriteAsync\_DSharpPlus\_Entities\_DiscordMember\_DSharpPlus\_Permissions\_DSharpPlus\_Permissions\_System\_String\_), 
[DiscordChannel.AddOverwriteAsync\(DiscordRole, Permissions, Permissions, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_AddOverwriteAsync\_DSharpPlus\_Entities\_DiscordRole\_DSharpPlus\_Permissions\_DSharpPlus\_Permissions\_System\_String\_), 
[DiscordChannel.DeleteOverwriteAsync\(DiscordMember, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_DeleteOverwriteAsync\_DSharpPlus\_Entities\_DiscordMember\_System\_String\_), 
[DiscordChannel.DeleteOverwriteAsync\(DiscordRole, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_DeleteOverwriteAsync\_DSharpPlus\_Entities\_DiscordRole\_System\_String\_), 
[DiscordChannel.TriggerTypingAsync\(\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_TriggerTypingAsync), 
[DiscordChannel.GetPinnedMessagesAsync\(\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetPinnedMessagesAsync), 
[DiscordChannel.CreateWebhookAsync\(string, Optional<Stream\>, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CreateWebhookAsync\_System\_String\_DSharpPlus\_Entities\_Optional\_System\_IO\_Stream\_\_System\_String\_), 
[DiscordChannel.GetWebhooksAsync\(\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetWebhooksAsync), 
[DiscordChannel.PlaceMemberAsync\(DiscordMember\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_PlaceMemberAsync\_DSharpPlus\_Entities\_DiscordMember\_), 
[DiscordChannel.FollowAsync\(DiscordChannel\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_FollowAsync\_DSharpPlus\_Entities\_DiscordChannel\_), 
[DiscordChannel.CrosspostMessageAsync\(DiscordMessage\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CrosspostMessageAsync\_DSharpPlus\_Entities\_DiscordMessage\_), 
[DiscordChannel.UpdateCurrentUserVoiceStateAsync\(bool?, DateTimeOffset?\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_UpdateCurrentUserVoiceStateAsync\_System\_Nullable\_System\_Boolean\_\_System\_Nullable\_System\_DateTimeOffset\_\_), 
[DiscordChannel.CreateStageInstanceAsync\(string, PrivacyLevel?, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CreateStageInstanceAsync\_System\_String\_System\_Nullable\_DSharpPlus\_PrivacyLevel\_\_System\_String\_), 
[DiscordChannel.GetStageInstanceAsync\(\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetStageInstanceAsync), 
[DiscordChannel.ModifyStageInstanceAsync\(Action<StageInstanceEditModel\>\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ModifyStageInstanceAsync\_System\_Action\_DSharpPlus\_Net\_Models\_StageInstanceEditModel\_\_), 
[DiscordChannel.DeleteStageInstanceAsync\(string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_DeleteStageInstanceAsync\_System\_String\_), 
[DiscordChannel.PermissionsFor\(DiscordMember\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_PermissionsFor\_DSharpPlus\_Entities\_DiscordMember\_), 
[DiscordChannel.ToString\(\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_ToString), 
[DiscordChannel.CreateThreadAsync\(DiscordMessage, string, AutoArchiveDuration, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CreateThreadAsync\_DSharpPlus\_Entities\_DiscordMessage\_System\_String\_DSharpPlus\_AutoArchiveDuration\_System\_String\_), 
[DiscordChannel.CreateThreadAsync\(string, AutoArchiveDuration, ChannelType, string\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_CreateThreadAsync\_System\_String\_DSharpPlus\_AutoArchiveDuration\_DSharpPlus\_ChannelType\_System\_String\_), 
[DiscordChannel.Equals\(object\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Equals\_System\_Object\_), 
[DiscordChannel.Equals\(DiscordChannel\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_Equals\_DSharpPlus\_Entities\_DiscordChannel\_), 
[DiscordChannel.GetHashCode\(\)](DSharpPlus.Entities.DiscordChannel.md\#DSharpPlus\_Entities\_DiscordChannel\_GetHashCode), 
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

### <a id="DSharpPlus_Entities_DiscordDmChannel_ApplicationId"></a>ApplicationId

Gets the application ID of the direct message's creator if it a bot.

```csharp
[JsonProperty("application_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ApplicationId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordDmChannel_IconHash"></a>IconHash

Gets the hash of this channel's icon.

```csharp
[JsonProperty("icon", NullValueHandling = NullValueHandling.Ignore)]
public string IconHash { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordDmChannel_IconUrl"></a>IconUrl

Gets the URL of this channel's icon.

```csharp
[JsonIgnore]
public string IconUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordDmChannel_OwnerId"></a>OwnerId

Gets the ID of this direct message's creator.

```csharp
[JsonProperty("owner_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong OwnerId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordDmChannel_Recipients"></a>Recipients

Gets the recipients of this direct message.

```csharp
[JsonProperty("recipients", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<DiscordUser> Recipients { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

## Methods

### <a id="DSharpPlus_Entities_DiscordDmChannel_AddDmRecipientAsync_System_UInt64_System_String_System_String_"></a>AddDmRecipientAsync\(ulong, string, string\)

Only use for Group DMs! Whitelisted bots only. Requires user's oauth2 access token

```csharp
public Task AddDmRecipientAsync(ulong user_id, string accesstoken, string nickname)
```

#### Parameters

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the user to add.

`accesstoken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The OAuth2 access token.

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

The nickname to give to the user.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordDmChannel_RemoveDmRecipientAsync_System_UInt64_System_String_"></a>RemoveDmRecipientAsync\(ulong, string\)

Only use for Group DMs!

```csharp
public Task RemoveDmRecipientAsync(ulong user_id, string accesstoken)
```

#### Parameters

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the User to remove.

`accesstoken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The OAuth2 access token.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

