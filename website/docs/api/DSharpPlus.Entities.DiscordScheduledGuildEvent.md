# Class DiscordScheduledGuildEvent

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

A scheduled event on a guild, which notifies all people that are interested in it.

```csharp
public sealed class DiscordScheduledGuildEvent : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Channel"></a>Channel

The channel this event is scheduled for, if applicable.

```csharp
[JsonIgnore]
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_ChannelId"></a>ChannelId

The id of the channel this event is scheduled in, if any.

```csharp
[JsonProperty("channel_id")]
public ulong? ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Creator"></a>Creator

The user that created this event.

```csharp
[JsonProperty("creator")]
public DiscordUser Creator { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Description"></a>Description

The description

```csharp
[JsonProperty("description")]
public string Description { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_EndTime"></a>EndTime

The time at which the event will end, or null if it doesn't have an end time.

```csharp
[JsonProperty("scheduled_end_time")]
public DateTimeOffset? EndTime { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Guild"></a>Guild

The guild this event is scheduled for.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_GuildId"></a>GuildId

The id of the guild this event is scheduled for.

```csharp
[JsonProperty("guild_id")]
public ulong GuildId { get; set; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Metadata"></a>Metadata

Metadata associated with this event.

```csharp
[JsonProperty("entity_metadata")]
public DiscordScheduledGuildEventMetadata Metadata { get; }
```

#### Property Value

[DiscordScheduledGuildEventMetadata](DSharpPlus.Entities.DiscordScheduledGuildEventMetadata.md)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Name"></a>Name

The name of the event.

```csharp
[JsonProperty("name")]
public string Name { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_PrivacyLevel"></a>PrivacyLevel

The privacy of this event.

```csharp
[JsonProperty("privacy_level")]
public ScheduledGuildEventPrivacyLevel PrivacyLevel { get; }
```

#### Property Value

[ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_StartTime"></a>StartTime

The time at which this event will begin.

```csharp
[JsonProperty("scheduled_start_time")]
public DateTimeOffset StartTime { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Status"></a>Status

The current status of this event.

```csharp
[JsonProperty("status")]
public ScheduledGuildEventStatus Status { get; }
```

#### Property Value

[ScheduledGuildEventStatus](DSharpPlus.Entities.ScheduledGuildEventStatus.md)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_Type"></a>Type

What type of event this is.

```csharp
[JsonProperty("entity_type")]
public ScheduledGuildEventType Type { get; }
```

#### Property Value

[ScheduledGuildEventType](DSharpPlus.Entities.ScheduledGuildEventType.md)

### <a id="DSharpPlus_Entities_DiscordScheduledGuildEvent_UserCount"></a>UserCount

How many users are interested in this event.

```csharp
[JsonProperty("user_count")]
public int? UserCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

