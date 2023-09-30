# Enum DiscordIntents

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents gateway intents to be specified for connecting to Discord.

```csharp
[Flags]
public enum DiscordIntents
```

###### Extension Methods

[DiscordIntentExtensions.AddIntent\(DiscordIntents, DiscordIntents\)](DSharpPlus.DiscordIntentExtensions.md\#DSharpPlus\_DiscordIntentExtensions\_AddIntent\_DSharpPlus\_DiscordIntents\_DSharpPlus\_DiscordIntents\_), 
[ExtensionMethods.GetName<DiscordIntents\>\(DiscordIntents\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_), 
[DiscordIntentExtensions.HasIntent\(DiscordIntents, DiscordIntents\)](DSharpPlus.DiscordIntentExtensions.md\#DSharpPlus\_DiscordIntentExtensions\_HasIntent\_DSharpPlus\_DiscordIntents\_DSharpPlus\_DiscordIntents\_), 
[DiscordIntentExtensions.RemoveIntent\(DiscordIntents, DiscordIntents\)](DSharpPlus.DiscordIntentExtensions.md\#DSharpPlus\_DiscordIntentExtensions\_RemoveIntent\_DSharpPlus\_DiscordIntents\_DSharpPlus\_DiscordIntents\_)

## Fields

`All = 3276799` 

Includes all intents.
<p>The <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intents are privileged, and must be enabled on the bot's developer page.</p>

`AllUnprivileged = 3243773` 

Includes all unprivileged intents.
<p>These are all intents excluding <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref>.</p>

`AutoModerationEvents = 1048576` 

Whetever to include creation, modification or deletion of an auto-Moderation rule.

`AutoModerationExecution = 2097152` 

Whetever to include when an auto-moderation rule was fired.

`DirectMessageReactions = 8192` 

Whether to include direct message reaction events.
<p>These include <xref href="DSharpPlus.DiscordClient.MessageReactionAdded" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.MessageReactionRemoved" data-throw-if-not-resolved="false"></xref>,</p>
<p><xref href="DSharpPlus.DiscordClient.MessageReactionsCleared" data-throw-if-not-resolved="false"></xref>, and <xref href="DSharpPlus.DiscordClient.MessageReactionRemovedEmoji" data-throw-if-not-resolved="false"></xref>.</p>
<p>These events only fire for DM channels.</p>

`DirectMessageTyping = 16384` 

Whether to include direct message typing events.
<p>This includes <xref href="DSharpPlus.DiscordClient.TypingStarted" data-throw-if-not-resolved="false"></xref>.</p>
<p>This event only fires for DM channels.</p>

`DirectMessages = 4096` 

Whether to include general direct message events.
<p>These include <xref href="DSharpPlus.DiscordClient.ChannelCreated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.MessageCreated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.MessageUpdated" data-throw-if-not-resolved="false"></xref>, </p>
<p><xref href="DSharpPlus.DiscordClient.MessageDeleted" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.ChannelPinsUpdated" data-throw-if-not-resolved="false"></xref>.</p>
<p>These events only fire for DM channels.</p>

`GuildEmojisAndStickers = 8` 

Whether to include guild emoji events.
<p>This includes <xref href="DSharpPlus.DiscordClient.GuildEmojisUpdated" data-throw-if-not-resolved="false"></xref>.</p>

`GuildIntegrations = 16` 

Whether to include guild integration events.
<p>This includes <xref href="DSharpPlus.DiscordClient.GuildIntegrationsUpdated" data-throw-if-not-resolved="false"></xref>.</p>

`GuildInvites = 64` 

Whether to include guild invite events.
<p>These include <xref href="DSharpPlus.DiscordClient.InviteCreated" data-throw-if-not-resolved="false"></xref>, and <xref href="DSharpPlus.DiscordClient.InviteDeleted" data-throw-if-not-resolved="false"></xref>.</p>

`GuildMembers = 2` 

Whether to include guild member events.
<p>These include <xref href="DSharpPlus.DiscordClient.GuildMemberAdded" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildMemberUpdated" data-throw-if-not-resolved="false"></xref>, and <xref href="DSharpPlus.DiscordClient.GuildMemberRemoved" data-throw-if-not-resolved="false"></xref>.</p>
<p>This is a privileged intent, and must be enabled on the bot's developer page.</p>

`GuildMessageReactions = 1024` 

Whether to include guild reaction events.
<p>These include <xref href="DSharpPlus.DiscordClient.MessageReactionAdded" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.MessageReactionRemoved" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.MessageReactionsCleared" data-throw-if-not-resolved="false"></xref>,</p>
<p>and <xref href="DSharpPlus.DiscordClient.MessageReactionRemovedEmoji" data-throw-if-not-resolved="false"></xref>.</p>

`GuildMessageTyping = 2048` 

Whether to include guild typing events.
<p>These include <xref href="DSharpPlus.DiscordClient.TypingStarted" data-throw-if-not-resolved="false"></xref>.</p>

`GuildMessages = 512` 

Whether to include guild message events.
<p>These include <xref href="DSharpPlus.DiscordClient.MessageCreated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.MessageUpdated" data-throw-if-not-resolved="false"></xref>, and <xref href="DSharpPlus.DiscordClient.MessageDeleted" data-throw-if-not-resolved="false"></xref>.</p>

`GuildModeration = 4` 

Whether to include guild ban events.
<p>These include <xref href="DSharpPlus.DiscordClient.GuildBanAdded" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildBanRemoved" data-throw-if-not-resolved="false"></xref> and <xref href="DSharpPlus.DiscordClient.GuildAuditLogCreated" data-throw-if-not-resolved="false"></xref>.</p>

`GuildPresences = 256` 

Whether to include guild presence events.
<p>This includes <xref href="DSharpPlus.DiscordClient.PresenceUpdated" data-throw-if-not-resolved="false"></xref>.</p>
<p>This is a privileged intent, and must be enabled on the bot's developer page.</p>

`GuildVoiceStates = 128` 

Whether to include guild voice state events.
<p>This includes <xref href="DSharpPlus.DiscordClient.VoiceStateUpdated" data-throw-if-not-resolved="false"></xref>.</p>

`GuildWebhooks = 32` 

Whether to include guild webhook events.
<p>This includes <xref href="DSharpPlus.DiscordClient.WebhooksUpdated" data-throw-if-not-resolved="false"></xref>.</p>

`Guilds = 1` 

Whether to include general guild events.
<p>These include <xref href="DSharpPlus.DiscordClient.GuildCreated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildDeleted" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildAvailable" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildDownloadCompleted" data-throw-if-not-resolved="false"></xref>,</p>
<p><xref href="DSharpPlus.DiscordClient.GuildRoleCreated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildRoleUpdated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildRoleDeleted" data-throw-if-not-resolved="false"></xref>,</p>
<p><xref href="DSharpPlus.DiscordClient.ChannelCreated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.ChannelUpdated" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.ChannelDeleted" data-throw-if-not-resolved="false"></xref>, and <xref href="DSharpPlus.DiscordClient.ChannelPinsUpdated" data-throw-if-not-resolved="false"></xref>.</p>

`MessageContents = 32768` 

Whether to include message content. This is a privileged event.
<p>Message content includes text, attachments, embeds, components, and reply content.</p>
<p>This intent is required for CommandsNext to function correctly.</p>

`None = 0` 

By default, no Discord Intents are requested from the Discord gateway.

`ScheduledGuildEvents = 65536` 

Whether to include scheduled event messages.

