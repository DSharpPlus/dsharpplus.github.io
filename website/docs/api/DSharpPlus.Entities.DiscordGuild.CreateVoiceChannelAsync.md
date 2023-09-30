# Method CreateVoiceChannelAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateVoiceChannelAsync_System_String_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_Int32__System_Nullable_System_Int32__System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_DSharpPlus_VideoQualityMode__System_Nullable_System_Int32__System_String_"></a>CreateVoiceChannelAsync\(string, DiscordChannel, int?, int?, IEnumerable<DiscordOverwriteBuilder\>, VideoQualityMode?, int?, string\)

Creates a new voice channel in this guild.

```csharp
public Task<DiscordChannel> CreateVoiceChannelAsync(string name, DiscordChannel parent = null, int? bitrate = null, int? userLimit = null, IEnumerable<DiscordOverwriteBuilder> overwrites = null, VideoQualityMode? qualityMode = null, int? position = null, string reason = null)
```

### Parameters

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

