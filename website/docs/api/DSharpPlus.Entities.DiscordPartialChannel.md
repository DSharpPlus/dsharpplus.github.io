# Class DiscordPartialChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

A partial channel object

```csharp
public class DiscordPartialChannel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordPartialChannel](DSharpPlus.Entities.DiscordPartialChannel.md)

## Remarks

Partial objects can have any or no data, but the ID is always returned

## Fields

### <a id="DSharpPlus_Entities_DiscordPartialChannel_PermissionOverwrites"></a>PermissionOverwrites

Gets a list of permission overwrites

```csharp
[JsonProperty("permission_overwrites", NullValueHandling = NullValueHandling.Ignore)]
public List<DiscordOverwrite>? PermissionOverwrites
```

#### Field Value

[List](https://learn.microsoft.com/dotnet/api/system.collections.generic.list\-1)<[DiscordOverwrite](DSharpPlus.Entities.DiscordOverwrite.md)\>?

## Properties

### <a id="DSharpPlus_Entities_DiscordPartialChannel_Bitrate"></a>Bitrate

Gets this channel's bitrate. This is applicable to voice channels only.

```csharp
[JsonProperty("bitrate", NullValueHandling = NullValueHandling.Ignore)]
public int? Bitrate { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_GuildId"></a>GuildId

Gets ID of the guild to which this channel belongs.

```csharp
[JsonProperty("guild_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_Id"></a>Id

Gets the ID of this object.

```csharp
[JsonProperty("id", NullValueHandling = NullValueHandling.Ignore)]
public ulong Id { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordPartialChannel_IsNsfw"></a>IsNsfw

Gets whether this channel is an NSFW channel.

```csharp
[JsonProperty("nsfw", NullValueHandling = NullValueHandling.Ignore)]
public bool? IsNsfw { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_LastMessageId"></a>LastMessageId

Gets the ID of the last message sent in this channel. This is applicable to text channels only.

```csharp
[JsonProperty("last_message_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? LastMessageId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

#### Remarks

For forum posts, this ID may point to an invalid message (e.g. the OP deleted the initial forum message).

### <a id="DSharpPlus_Entities_DiscordPartialChannel_LastPinTimestamp"></a>LastPinTimestamp

Gets when the last pinned message was pinned.

```csharp
[JsonProperty("last_pin_timestamp", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? LastPinTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_Name"></a>Name

Gets the name of this channel.

```csharp
[JsonProperty("name", NullValueHandling = NullValueHandling.Ignore)]
public string? Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_ParentId"></a>ParentId

Gets ID of the category that contains this channel. For threads, gets the ID of the channel this thread was created in.

```csharp
[JsonProperty("parent_id", NullValueHandling = NullValueHandling.Include)]
public ulong? ParentId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_PerUserRateLimit"></a>PerUserRateLimit

<p>Gets the slow mode delay configured for this channel.</p>
<p>All bots, as well as users with <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permissions in the channel are exempt from slow mode.</p>

```csharp
[JsonProperty("rate_limit_per_user", NullValueHandling = NullValueHandling.Ignore)]
public int? PerUserRateLimit { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_Position"></a>Position

Gets the position of this channel.

```csharp
[JsonProperty("position", NullValueHandling = NullValueHandling.Ignore)]
public int? Position { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_QualityMode"></a>QualityMode

Gets this channel's video quality mode. This is applicable to voice channels only.

```csharp
[JsonProperty("video_quality_mode", NullValueHandling = NullValueHandling.Ignore)]
public VideoQualityMode? QualityMode { get; }
```

#### Property Value

[VideoQualityMode](DSharpPlus.VideoQualityMode.md)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_RtcRegionId"></a>RtcRegionId

Get the name of the voice region

```csharp
[JsonProperty("rtc_region", NullValueHandling = NullValueHandling.Ignore)]
public string? RtcRegionId { get; set; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_Topic"></a>Topic

Gets the channel's topic. This is applicable to text channels only.

```csharp
[JsonProperty("topic", NullValueHandling = NullValueHandling.Ignore)]
public string? Topic { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_Type"></a>Type

Gets the type of this channel.

```csharp
[JsonProperty("type", NullValueHandling = NullValueHandling.Ignore)]
public ChannelType? Type { get; }
```

#### Property Value

[ChannelType](DSharpPlus.ChannelType.md)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_UserLimit"></a>UserLimit

Gets this channel's user limit. This is applicable to voice channels only.

```csharp
[JsonProperty("user_limit", NullValueHandling = NullValueHandling.Ignore)]
public int? UserLimit { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

### <a id="DSharpPlus_Entities_DiscordPartialChannel_UserPermissions"></a>UserPermissions

Gets the permissions of the user who invoked the command in this channel.
<p>Only sent on the resolved channels of interaction responses for application commands.</p>

```csharp
[JsonProperty("permissions", NullValueHandling = NullValueHandling.Ignore)]
public Permissions? UserPermissions { get; }
```

#### Property Value

[Permissions](DSharpPlus.Permissions.md)?

