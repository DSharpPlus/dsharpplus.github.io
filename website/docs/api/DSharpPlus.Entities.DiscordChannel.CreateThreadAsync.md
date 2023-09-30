# Method CreateThreadAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_CreateThreadAsync_DSharpPlus_Entities_DiscordMessage_System_String_DSharpPlus_AutoArchiveDuration_System_String_"></a>CreateThreadAsync\(DiscordMessage, string, AutoArchiveDuration, string\)

Creates a new thread within this channel from the given message.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(DiscordMessage message, string name, AutoArchiveDuration archiveAfter, string reason = null)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to create the thread from.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration of the thread.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

The created thread.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel or message does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordChannel_CreateThreadAsync_System_String_DSharpPlus_AutoArchiveDuration_DSharpPlus_ChannelType_System_String_"></a>CreateThreadAsync\(string, AutoArchiveDuration, ChannelType, string\)

Creates a new thread within this channel.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(string name, AutoArchiveDuration archiveAfter, ChannelType threadType, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration of the thread.

`threadType` [ChannelType](DSharpPlus.ChannelType.md)

The type of thread to create, either a public, news or, private thread.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

The created thread.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel or message does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

