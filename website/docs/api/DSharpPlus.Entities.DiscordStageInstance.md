# Class DiscordStageInstance

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a discord stage instance.

```csharp
public sealed class DiscordStageInstance : SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md) ← 
[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)

###### Inherited Members

[SnowflakeObject.Id](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_Id), 
[SnowflakeObject.CreationTimestamp](DSharpPlus.Entities.SnowflakeObject.md\#DSharpPlus\_Entities\_SnowflakeObject\_CreationTimestamp)

## Properties

### <a id="DSharpPlus_Entities_DiscordStageInstance_Channel"></a>Channel

Gets the channel this stage instance is in.

```csharp
[JsonIgnore]
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordStageInstance_ChannelId"></a>ChannelId

Gets the id of the channel this stage instance is in.

```csharp
[JsonProperty("channel_id")]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordStageInstance_DiscoverableDisabled"></a>DiscoverableDisabled

Gets whether or not stage discovery is disabled.

```csharp
[JsonProperty("discoverable_disabled")]
public bool DiscoverableDisabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_DiscordStageInstance_Guild"></a>Guild

Gets the guild this stage instance is in.

```csharp
[JsonIgnore]
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_Entities_DiscordStageInstance_GuildId"></a>GuildId

Gets the id of the guild this stage instance is in.

```csharp
[JsonProperty("guild_id")]
public ulong GuildId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordStageInstance_PrivacyLevel"></a>PrivacyLevel

Gets the privacy level of this stage instance.

```csharp
[JsonProperty("privacy_level")]
public PrivacyLevel PrivacyLevel { get; }
```

#### Property Value

[PrivacyLevel](DSharpPlus.PrivacyLevel.md)

### <a id="DSharpPlus_Entities_DiscordStageInstance_Topic"></a>Topic

Gets the topic of this stage instance.

```csharp
[JsonProperty("topic")]
public string Topic { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

## Methods

### <a id="DSharpPlus_Entities_DiscordStageInstance_BecomeSpeakerAsync"></a>BecomeSpeakerAsync\(\)

Become speaker of current stage.

```csharp
public Task BecomeSpeakerAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.MoveMembers" data-throw-if-not-resolved="false"></xref> permission

### <a id="DSharpPlus_Entities_DiscordStageInstance_InviteToSpeakAsync_DSharpPlus_Entities_DiscordMember_"></a>InviteToSpeakAsync\(DiscordMember\)

Invite a member to become a speaker in the state instance.

```csharp
public Task InviteToSpeakAsync(DiscordMember member)
```

#### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to invite to speak on stage.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.MoveMembers" data-throw-if-not-resolved="false"></xref> permission

### <a id="DSharpPlus_Entities_DiscordStageInstance_SendSpeakerRequestAsync"></a>SendSpeakerRequestAsync\(\)

Request to become a speaker in the stage instance.

```csharp
public Task SendSpeakerRequestAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.RequestToSpeak" data-throw-if-not-resolved="false"></xref> permission

