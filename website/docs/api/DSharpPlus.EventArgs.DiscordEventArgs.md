# Class DiscordEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Common base for all other <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref>-related event argument classes.

```csharp
public abstract class DiscordEventArgs : AsyncEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md)

###### Derived

[ApplicationCommandEventArgs](DSharpPlus.EventArgs.ApplicationCommandEventArgs.md), 
[ApplicationCommandPermissionsUpdatedEventArgs](DSharpPlus.EventArgs.ApplicationCommandPermissionsUpdatedEventArgs.md), 
[AutoModerationRuleCreateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleCreateEventArgs.md), 
[AutoModerationRuleDeleteEventArgs](DSharpPlus.EventArgs.AutoModerationRuleDeleteEventArgs.md), 
[AutoModerationRuleExecuteEventArgs](DSharpPlus.EventArgs.AutoModerationRuleExecuteEventArgs.md), 
[AutoModerationRuleUpdateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleUpdateEventArgs.md), 
[ChannelCreateEventArgs](DSharpPlus.EventArgs.ChannelCreateEventArgs.md), 
[ChannelDeleteEventArgs](DSharpPlus.EventArgs.ChannelDeleteEventArgs.md), 
[ChannelPinsUpdateEventArgs](DSharpPlus.EventArgs.ChannelPinsUpdateEventArgs.md), 
[ChannelUpdateEventArgs](DSharpPlus.EventArgs.ChannelUpdateEventArgs.md), 
[ClientErrorEventArgs](DSharpPlus.EventArgs.ClientErrorEventArgs.md), 
[DmChannelDeleteEventArgs](DSharpPlus.EventArgs.DmChannelDeleteEventArgs.md), 
[GuildAuditLogCreatedEventArgs](DSharpPlus.EventArgs.GuildAuditLogCreatedEventArgs.md), 
[GuildBanAddEventArgs](DSharpPlus.EventArgs.GuildBanAddEventArgs.md), 
[GuildBanRemoveEventArgs](DSharpPlus.EventArgs.GuildBanRemoveEventArgs.md), 
[GuildCreateEventArgs](DSharpPlus.EventArgs.GuildCreateEventArgs.md), 
[GuildDeleteEventArgs](DSharpPlus.EventArgs.GuildDeleteEventArgs.md), 
[GuildDownloadCompletedEventArgs](DSharpPlus.EventArgs.GuildDownloadCompletedEventArgs.md), 
[GuildEmojisUpdateEventArgs](DSharpPlus.EventArgs.GuildEmojisUpdateEventArgs.md), 
[GuildIntegrationsUpdateEventArgs](DSharpPlus.EventArgs.GuildIntegrationsUpdateEventArgs.md), 
[GuildMemberAddEventArgs](DSharpPlus.EventArgs.GuildMemberAddEventArgs.md), 
[GuildMemberRemoveEventArgs](DSharpPlus.EventArgs.GuildMemberRemoveEventArgs.md), 
[GuildMemberUpdateEventArgs](DSharpPlus.EventArgs.GuildMemberUpdateEventArgs.md), 
[GuildMembersChunkEventArgs](DSharpPlus.EventArgs.GuildMembersChunkEventArgs.md), 
[GuildRoleCreateEventArgs](DSharpPlus.EventArgs.GuildRoleCreateEventArgs.md), 
[GuildRoleDeleteEventArgs](DSharpPlus.EventArgs.GuildRoleDeleteEventArgs.md), 
[GuildRoleUpdateEventArgs](DSharpPlus.EventArgs.GuildRoleUpdateEventArgs.md), 
[GuildStickersUpdateEventArgs](DSharpPlus.EventArgs.GuildStickersUpdateEventArgs.md), 
[GuildUpdateEventArgs](DSharpPlus.EventArgs.GuildUpdateEventArgs.md), 
[HeartbeatEventArgs](DSharpPlus.EventArgs.HeartbeatEventArgs.md), 
[IntegrationCreateEventArgs](DSharpPlus.EventArgs.IntegrationCreateEventArgs.md), 
[IntegrationDeleteEventArgs](DSharpPlus.EventArgs.IntegrationDeleteEventArgs.md), 
[IntegrationUpdateEventArgs](DSharpPlus.EventArgs.IntegrationUpdateEventArgs.md), 
[InteractionCreateEventArgs](DSharpPlus.EventArgs.InteractionCreateEventArgs.md), 
[InviteCreateEventArgs](DSharpPlus.EventArgs.InviteCreateEventArgs.md), 
[InviteDeleteEventArgs](DSharpPlus.EventArgs.InviteDeleteEventArgs.md), 
[MessageAcknowledgeEventArgs](DSharpPlus.EventArgs.MessageAcknowledgeEventArgs.md), 
[MessageBulkDeleteEventArgs](DSharpPlus.EventArgs.MessageBulkDeleteEventArgs.md), 
[MessageCreateEventArgs](DSharpPlus.EventArgs.MessageCreateEventArgs.md), 
[MessageDeleteEventArgs](DSharpPlus.EventArgs.MessageDeleteEventArgs.md), 
[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md), 
[MessageReactionRemoveEmojiEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEmojiEventArgs.md), 
[MessageReactionRemoveEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEventArgs.md), 
[MessageReactionsClearEventArgs](DSharpPlus.EventArgs.MessageReactionsClearEventArgs.md), 
[MessageUpdateEventArgs](DSharpPlus.EventArgs.MessageUpdateEventArgs.md), 
[PresenceUpdateEventArgs](DSharpPlus.EventArgs.PresenceUpdateEventArgs.md), 
[ScheduledGuildEventCompletedEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventCompletedEventArgs.md), 
[ScheduledGuildEventCreateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventCreateEventArgs.md), 
[ScheduledGuildEventDeleteEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventDeleteEventArgs.md), 
[ScheduledGuildEventUpdateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUpdateEventArgs.md), 
[ScheduledGuildEventUserAddEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md), 
[SessionReadyEventArgs](DSharpPlus.EventArgs.SessionReadyEventArgs.md), 
[SocketCloseEventArgs](DSharpPlus.EventArgs.SocketCloseEventArgs.md), 
[SocketErrorEventArgs](DSharpPlus.EventArgs.SocketErrorEventArgs.md), 
[SocketEventArgs](DSharpPlus.EventArgs.SocketEventArgs.md), 
[StageInstanceCreateEventArgs](DSharpPlus.EventArgs.StageInstanceCreateEventArgs.md), 
[StageInstanceDeleteEventArgs](DSharpPlus.EventArgs.StageInstanceDeleteEventArgs.md), 
[StageInstanceUpdateEventArgs](DSharpPlus.EventArgs.StageInstanceUpdateEventArgs.md), 
[ThreadCreateEventArgs](DSharpPlus.EventArgs.ThreadCreateEventArgs.md), 
[ThreadDeleteEventArgs](DSharpPlus.EventArgs.ThreadDeleteEventArgs.md), 
[ThreadListSyncEventArgs](DSharpPlus.EventArgs.ThreadListSyncEventArgs.md), 
[ThreadMemberUpdateEventArgs](DSharpPlus.EventArgs.ThreadMemberUpdateEventArgs.md), 
[ThreadMembersUpdateEventArgs](DSharpPlus.EventArgs.ThreadMembersUpdateEventArgs.md), 
[ThreadUpdateEventArgs](DSharpPlus.EventArgs.ThreadUpdateEventArgs.md), 
[TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md), 
[UnknownEventArgs](DSharpPlus.EventArgs.UnknownEventArgs.md), 
[UserSettingsUpdateEventArgs](DSharpPlus.EventArgs.UserSettingsUpdateEventArgs.md), 
[UserSpeakingEventArgs](DSharpPlus.EventArgs.UserSpeakingEventArgs.md), 
[UserUpdateEventArgs](DSharpPlus.EventArgs.UserUpdateEventArgs.md), 
[VoiceReceiveEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceReceiveEventArgs.md), 
[VoiceServerUpdateEventArgs](DSharpPlus.EventArgs.VoiceServerUpdateEventArgs.md), 
[VoiceStateUpdateEventArgs](DSharpPlus.EventArgs.VoiceStateUpdateEventArgs.md), 
[VoiceUserJoinEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceUserJoinEventArgs.md), 
[VoiceUserLeaveEventArgs](DSharpPlus.VoiceNext.EventArgs.VoiceUserLeaveEventArgs.md), 
[WebhooksUpdateEventArgs](DSharpPlus.EventArgs.WebhooksUpdateEventArgs.md), 
[ZombiedEventArgs](DSharpPlus.EventArgs.ZombiedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Constructors

### <a id="DSharpPlus_EventArgs_DiscordEventArgs__ctor"></a>DiscordEventArgs\(\)

```csharp
protected DiscordEventArgs()
```

