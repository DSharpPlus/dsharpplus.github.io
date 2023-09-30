# Method CreateChannelCategoryAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateChannelCategoryAsync_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordOverwriteBuilder__System_Nullable_System_Int32__System_String_"></a>CreateChannelCategoryAsync\(string, IEnumerable<DiscordOverwriteBuilder\>, int?, string\)

Creates a new channel category in this guild.

```csharp
public Task<DiscordChannel> CreateChannelCategoryAsync(string name, IEnumerable<DiscordOverwriteBuilder> overwrites = null, int? position = null, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the new category.

`overwrites` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordOverwriteBuilder](DSharpPlus.Entities.DiscordOverwriteBuilder.md)\>

Permission overwrites for this category.

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Sorting position of the channel.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

The newly-created channel category.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

