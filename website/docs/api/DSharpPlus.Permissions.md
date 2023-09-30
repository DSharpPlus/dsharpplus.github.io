# Enum Permissions

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Bitwise permission flags.

```csharp
[Flags]
public enum Permissions : long
```

###### Extension Methods

[ExtensionMethods.GetName<Permissions\>\(Permissions\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_), 
[PermissionMethods.Grant\(Permissions, Permissions\)](DSharpPlus.PermissionMethods.md\#DSharpPlus\_PermissionMethods\_Grant\_DSharpPlus\_Permissions\_DSharpPlus\_Permissions\_), 
[PermissionMethods.HasPermission\(Permissions, Permissions\)](DSharpPlus.PermissionMethods.md\#DSharpPlus\_PermissionMethods\_HasPermission\_DSharpPlus\_Permissions\_DSharpPlus\_Permissions\_), 
[PermissionMethods.Revoke\(Permissions, Permissions\)](DSharpPlus.PermissionMethods.md\#DSharpPlus\_PermissionMethods\_Revoke\_DSharpPlus\_Permissions\_DSharpPlus\_Permissions\_), 
[Utilities.ToPermissionString\(Permissions\)](DSharpPlus.Utilities.md\#DSharpPlus\_Utilities\_ToPermissionString\_DSharpPlus\_Permissions\_)

## Fields

`AccessChannels = 1024` 

Allows accessing text and voice channels. Disabling this permission hides channels.

`AddReactions = 64` 

Allows adding reactions to messages.

`Administrator = 8` 

Enables full access on a given guild. This also overrides other permissions.

`All = 2199023255551` 

Indicates all permissions are granted

`AttachFiles = 32768` 

Allows uploading files.

`BanMembers = 4` 

Allows banning and unbanning members.

`ChangeNickname = 67108864` 

Allows changing of own nickname.

`CreateInstantInvite = 1` 

Allows creation of instant channel invites.

`CreatePrivateThreads = 68719476736` 

Allows for creating private threads.

`CreatePublicThreads = 34359738368` 

Allows for creating public threads.

`DeafenMembers = 8388608` 

Allows deafening other members in voice chat.

`EmbedLinks = 16384` 

Allows embedding content in messages.

`KickMembers = 2` 

Allows kicking members.

`ManageChannels = 16` 

Allows managing channels.

`ManageEmojis = 1073741824` 

Allows managing guild emoji and stickers.

`ManageEvents = 8589934592` 

Allows for managing scheduled guild events.

`ManageGuild = 32` 

Allows managing the guild.

`ManageMessages = 8192` 

Allows managing messages of other users.

`ManageNicknames = 134217728` 

Allows managing nicknames of other members.

`ManageRoles = 268435456` 

Allows managing roles in a guild.

`ManageThreads = 17179869184` 

Allows for deleting and archiving threads, and viewing all private threads.

`ManageWebhooks = 536870912` 

Allows managing webhooks in a guild.

`MentionEveryone = 131072` 

Allows using @everyone and @here mentions.

`ModerateMembers = 1099511627776` 

Allows for moderating (Timeout) members in a guild.

`MoveMembers = 16777216` 

Allows moving voice chat members.

`MuteMembers = 4194304` 

Allows muting other members in voice chat.

`None = 0` 

Indicates no permissions given.

`PrioritySpeaker = 256` 

Allows the use of priority speaker.

`ReadMessageHistory = 65536` 

Allows reading message history.

`RequestToSpeak = 4294967296` 

Allows for requesting to speak in stage channels.

`SendMessages = 2048` 

Allows sending messages (does not allow sending messages in threads).

`SendMessagesInThreads = 274877906944` 

Allows for sending messages in threads.

`SendTtsMessages = 4096` 

Allows sending text-to-speech messages.

`Speak = 2097152` 

Allows speaking in voice chat.

`StartEmbeddedActivities = 549755813888` 

Allows for launching activities (applications with the `EMBEDDED` flag) in a voice channel.

`Stream = 512` 

Allows the user to go live.

`UseApplicationCommands = 2147483648` 

Allows the user to use application commands.

`UseExternalEmojis = 262144` 

Allows using emojis or stickers from external servers, such as twitch or nitro emojis.

`UseExternalStickers = 137438953472` 

Allows the usage of custom stickers from other servers.

`UseVoice = 1048576` 

Allows connecting to voice chat.

`UseVoiceDetection = 33554432` 

Allows using voice activation in voice chat. Revoking this will usage of push-to-talk.

`ViewAuditLog = 128` 

Allows viewing audit log entries.

