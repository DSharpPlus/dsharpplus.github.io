# Class DiscordWebhook

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents information about a Discord webhook.

```csharp
public class DiscordWebhook : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordWebhook_AvatarUrl"></a>AvatarUrl

Gets the default avatar url for this webhook.

```csharp
public string AvatarUrl { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWebhook_ChannelId"></a>ChannelId

Gets the ID of the channel this webhook belongs to.

```csharp
[JsonProperty("channel_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordWebhook_GuildId"></a>GuildId

Gets the ID of the guild this webhook belongs to.

```csharp
[JsonProperty("guild_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordWebhook_Name"></a>Name

Gets the default name of this webhook.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWebhook_SourceChannel"></a>SourceChannel

A partial channel object for the channel this channel follower webhook is following.

```csharp
[JsonProperty("source_channel", NullValueHandling = NullValueHandling.Ignore)]
public DiscordPartialChannel SourceChannel { get; }
```

#### Property Value

[DiscordPartialChannel](DSharpPlus.Entities.DiscordPartialChannel.md)

### <a id="DSharpPlus_Entities_DiscordWebhook_SourceGuild"></a>SourceGuild

A partial guild object for the guild of the channel this channel follower webhook is following.

```csharp
[JsonProperty("source_guild", NullValueHandling = NullValueHandling.Ignore)]
public DiscordGuild SourceGuild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordWebhook_Token"></a>Token

Gets the secure token of this webhook.

```csharp
[JsonProperty("token", NullValueHandling = NullValueHandling.Ignore)]
public string Token { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWebhook_Url"></a>Url

Gets the webhook's url. Only returned when using the webhook.incoming OAuth2 scope.

```csharp
[JsonProperty("url", NullValueHandling = NullValueHandling.Ignore)]
public string Url { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordWebhook_User"></a>User

Gets the user this webhook was created by.

```csharp
[JsonProperty("user", NullValueHandling = NullValueHandling.Ignore)]
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_Entities_DiscordWebhook_DeleteAsync"></a>DeleteAsync\(\)

Permanently deletes this webhook.

```csharp
public Task DeleteAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordWebhook_DeleteMessageAsync_System_UInt64_"></a>DeleteMessageAsync\(ulong\)

Deletes a message that was created by the webhook.

```csharp
public Task DeleteMessageAsync(ulong messageId)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the message to delete

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordWebhook_EditMessageAsync_System_UInt64_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditMessageAsync\(ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits a previously-sent webhook message.

```csharp
public Task<DiscordMessage> EditMessageAsync(ulong messageId, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the message to edit.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The builder of the message to edit.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The modified <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordWebhook_Equals_System_Object_"></a>Equals\(object\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref> is equal to another object.

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

Object to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the object is equal to this <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordWebhook_Equals_DSharpPlus_Entities_DiscordWebhook_"></a>Equals\(DiscordWebhook\)

Checks whether this <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref> is equal to another <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref>.

```csharp
public bool Equals(DiscordWebhook e)
```

#### Parameters

`e` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

<xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref> to compare to.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref> is equal to this <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordWebhook_ExecuteAsync_DSharpPlus_Entities_DiscordWebhookBuilder_"></a>ExecuteAsync\(DiscordWebhookBuilder\)

Executes this webhook with the given <xref href="DSharpPlus.Entities.DiscordWebhookBuilder" data-throw-if-not-resolved="false"></xref>.

```csharp
public Task<DiscordMessage> ExecuteAsync(DiscordWebhookBuilder builder)
```

#### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

Webhook builder filled with data to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordWebhook_ExecuteGithubAsync_System_String_"></a>ExecuteGithubAsync\(string\)

Executes this webhook in GitHub compatibility mode.

```csharp
public Task ExecuteGithubAsync(string json)
```

#### Parameters

`json` [string](https://learn.microsoft.com/dotnet/api/system.string)

JSON containing GitHub-compatible payload for this webhook.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordWebhook_ExecuteSlackAsync_System_String_"></a>ExecuteSlackAsync\(string\)

Executes this webhook in Slack compatibility mode.

```csharp
public Task ExecuteSlackAsync(string json)
```

#### Parameters

`json` [string](https://learn.microsoft.com/dotnet/api/system.string)

JSON containing Slack-compatible payload for this webhook.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordWebhook_GetHashCode"></a>GetHashCode\(\)

Gets the hash code for this <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref>.

```csharp
public override int GetHashCode()
```

#### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

The hash code for this <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref>.

### <a id="DSharpPlus_Entities_DiscordWebhook_GetMessageAsync_System_UInt64_"></a>GetMessageAsync\(ulong\)

Gets a previously-sent webhook message.

```csharp
public Task<DiscordMessage> GetMessageAsync(ulong messageId)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook or message does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_Entities_DiscordWebhook_ModifyAsync_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__System_Nullable_System_UInt64__System_String_"></a>ModifyAsync\(string, Optional<Stream\>, ulong?, string\)

Modifies this webhook.

```csharp
public Task<DiscordWebhook> ModifyAsync(string name = null, Optional<Stream> avatar = default, ulong? channelId = null, string reason = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New default name for this webhook.

`avatar` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

New avatar for this webhook.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The new channel id to move the webhook to.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

The modified webhook.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## Operators

### <a id="DSharpPlus_Entities_DiscordWebhook_op_Equality_DSharpPlus_Entities_DiscordWebhook_DSharpPlus_Entities_DiscordWebhook_"></a>operator ==\(DiscordWebhook, DiscordWebhook\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref> objects are equal.

```csharp
public static bool operator ==(DiscordWebhook e1, DiscordWebhook e2)
```

#### Parameters

`e1` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

First webhook to compare.

`e2` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

Second webhook to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two webhooks are equal.

### <a id="DSharpPlus_Entities_DiscordWebhook_op_Inequality_DSharpPlus_Entities_DiscordWebhook_DSharpPlus_Entities_DiscordWebhook_"></a>operator \!=\(DiscordWebhook, DiscordWebhook\)

Gets whether the two <xref href="DSharpPlus.Entities.DiscordWebhook" data-throw-if-not-resolved="false"></xref> objects are not equal.

```csharp
public static bool operator !=(DiscordWebhook e1, DiscordWebhook e2)
```

#### Parameters

`e1` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

First webhook to compare.

`e2` [DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)

Second webhook to compare.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the two webhooks are not equal.

