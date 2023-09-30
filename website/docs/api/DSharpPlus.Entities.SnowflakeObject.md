# Class SnowflakeObject

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents an object in Discord API.

```csharp
public abstract class SnowflakeObject
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SnowflakeObject](DSharpPlus.Entities.SnowflakeObject.md)

###### Derived

[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md), 
[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md), 
[DiscordAuditLogEntry](DSharpPlus.Entities.AuditLogs.DiscordAuditLogEntry.md), 
[DiscordAutoModerationRule](DSharpPlus.Entities.DiscordAutoModerationRule.md), 
[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md), 
[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md), 
[DiscordForumTag](DSharpPlus.Entities.DiscordForumTag.md), 
[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md), 
[DiscordGuildApplicationCommandPermissions](DSharpPlus.Entities.DiscordGuildApplicationCommandPermissions.md), 
[DiscordGuildPreview](DSharpPlus.Entities.DiscordGuildPreview.md), 
[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md), 
[DiscordInteraction](DSharpPlus.Entities.DiscordInteraction.md), 
[DiscordInteractionData](DSharpPlus.Entities.DiscordInteractionData.md), 
[DiscordInviteChannel](DSharpPlus.Entities.DiscordInviteChannel.md), 
[DiscordInviteGuild](DSharpPlus.Entities.DiscordInviteGuild.md), 
[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md), 
[DiscordMessageApplication](DSharpPlus.Entities.DiscordMessageApplication.md), 
[DiscordMessageInteraction](DSharpPlus.Entities.DiscordMessageInteraction.md), 
[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md), 
[DiscordMessageStickerPack](DSharpPlus.Entities.DiscordMessageStickerPack.md), 
[DiscordOverwrite](DSharpPlus.Entities.DiscordOverwrite.md), 
[DiscordRole](DSharpPlus.Entities.DiscordRole.md), 
[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md), 
[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md), 
[DiscordTeam](DSharpPlus.Entities.DiscordTeam.md), 
[DiscordUser](DSharpPlus.Entities.DiscordUser.md), 
[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md), 
[DiscordWidget](DSharpPlus.Entities.DiscordWidget.md)

## Properties

### <a id="DSharpPlus_Entities_SnowflakeObject_CreationTimestamp"></a>CreationTimestamp

Gets the date and time this object was created.

```csharp
[JsonIgnore]
public DateTimeOffset CreationTimestamp { get; }
```

#### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

### <a id="DSharpPlus_Entities_SnowflakeObject_Id"></a>Id

Gets the ID of this object.

```csharp
[JsonProperty("id", NullValueHandling = NullValueHandling.Ignore)]
public ulong Id { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

