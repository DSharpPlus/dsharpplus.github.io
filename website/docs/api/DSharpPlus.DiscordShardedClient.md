# Class DiscordShardedClient

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

A Discord client that shards automatically.

```csharp
public sealed class DiscordShardedClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordShardedClient](DSharpPlus.DiscordShardedClient.md)

###### Extension Methods

[ExtensionMethods.GetCommandsNextAsync\(DiscordShardedClient\)](DSharpPlus.CommandsNext.ExtensionMethods.md\#DSharpPlus\_CommandsNext\_ExtensionMethods\_GetCommandsNextAsync\_DSharpPlus\_DiscordShardedClient\_), 
[ClientExtensions.GetInteractivityAsync\(DiscordShardedClient\)](DSharpPlus.Interactivity.Extensions.ClientExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ClientExtensions\_GetInteractivityAsync\_DSharpPlus\_DiscordShardedClient\_), 
[DiscordClientExtensions.GetLavalinkAsync\(DiscordShardedClient\)](DSharpPlus.Lavalink.DiscordClientExtensions.md\#DSharpPlus\_Lavalink\_DiscordClientExtensions\_GetLavalinkAsync\_DSharpPlus\_DiscordShardedClient\_), 
[DiscordClientExtensions.GetVoiceNextAsync\(DiscordShardedClient\)](DSharpPlus.VoiceNext.DiscordClientExtensions.md\#DSharpPlus\_VoiceNext\_DiscordClientExtensions\_GetVoiceNextAsync\_DSharpPlus\_DiscordShardedClient\_), 
[ExtensionMethods.UseCommandsNextAsync\(DiscordShardedClient, CommandsNextConfiguration\)](DSharpPlus.CommandsNext.ExtensionMethods.md\#DSharpPlus\_CommandsNext\_ExtensionMethods\_UseCommandsNextAsync\_DSharpPlus\_DiscordShardedClient\_DSharpPlus\_CommandsNext\_CommandsNextConfiguration\_), 
[ClientExtensions.UseInteractivityAsync\(DiscordShardedClient, InteractivityConfiguration\)](DSharpPlus.Interactivity.Extensions.ClientExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ClientExtensions\_UseInteractivityAsync\_DSharpPlus\_DiscordShardedClient\_DSharpPlus\_Interactivity\_InteractivityConfiguration\_), 
[DiscordClientExtensions.UseLavalinkAsync\(DiscordShardedClient\)](DSharpPlus.Lavalink.DiscordClientExtensions.md\#DSharpPlus\_Lavalink\_DiscordClientExtensions\_UseLavalinkAsync\_DSharpPlus\_DiscordShardedClient\_), 
[ExtensionMethods.UseSlashCommandsAsync\(DiscordShardedClient, SlashCommandsConfiguration\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_UseSlashCommandsAsync\_DSharpPlus\_DiscordShardedClient\_DSharpPlus\_SlashCommands\_SlashCommandsConfiguration\_), 
[DiscordClientExtensions.UseVoiceNextAsync\(DiscordShardedClient, VoiceNextConfiguration\)](DSharpPlus.VoiceNext.DiscordClientExtensions.md\#DSharpPlus\_VoiceNext\_DiscordClientExtensions\_UseVoiceNextAsync\_DSharpPlus\_DiscordShardedClient\_DSharpPlus\_VoiceNext\_VoiceNextConfiguration\_)

## Constructors

### <a id="DSharpPlus_DiscordShardedClient__ctor_DSharpPlus_DiscordConfiguration_"></a>DiscordShardedClient\(DiscordConfiguration\)

Initializes new auto-sharding Discord client.

```csharp
public DiscordShardedClient(DiscordConfiguration config)
```

#### Parameters

`config` [DiscordConfiguration](DSharpPlus.DiscordConfiguration.md)

Configuration to use.

## Properties

### <a id="DSharpPlus_DiscordShardedClient_CurrentApplication"></a>CurrentApplication

Gets the current application.

```csharp
public DiscordApplication CurrentApplication { get; }
```

#### Property Value

[DiscordApplication](DSharpPlus.Entities.DiscordApplication.md)

### <a id="DSharpPlus_DiscordShardedClient_CurrentUser"></a>CurrentUser

Gets the current user.

```csharp
public DiscordUser CurrentUser { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_DiscordShardedClient_GatewayInfo"></a>GatewayInfo

Gets the gateway info for the client's session.

```csharp
public GatewayInfo GatewayInfo { get; }
```

#### Property Value

[GatewayInfo](DSharpPlus.Net.GatewayInfo.md)

### <a id="DSharpPlus_DiscordShardedClient_Logger"></a>Logger

Gets the logger for this client.

```csharp
public ILogger<BaseDiscordClient> Logger { get; }
```

#### Property Value

[ILogger](https://learn.microsoft.com/dotnet/api/microsoft.extensions.logging.ilogger\-1)<[BaseDiscordClient](DSharpPlus.BaseDiscordClient.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ShardClients"></a>ShardClients

Gets all client shards.

```csharp
public IReadOnlyDictionary<int, DiscordClient> ShardClients { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [DiscordClient](DSharpPlus.DiscordClient.md)\>

### <a id="DSharpPlus_DiscordShardedClient_VoiceRegions"></a>VoiceRegions

Gets the list of available voice regions. Note that this property will not contain VIP voice regions.

```csharp
public IReadOnlyDictionary<string, DiscordVoiceRegion> VoiceRegions { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[string](https://learn.microsoft.com/dotnet/api/system.string), [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)\>

## Methods

### <a id="DSharpPlus_DiscordShardedClient_Finalize"></a>\~DiscordShardedClient\(\)

```csharp
protected ~DiscordShardedClient()
```

### <a id="DSharpPlus_DiscordShardedClient_GetShard_System_UInt64_"></a>GetShard\(ulong\)

Gets a shard from a guild ID.
<p>
    If automatically sharding, this will use the <xref href="DSharpPlus.Utilities.GetShardId(System.UInt64%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref> method.
    Otherwise if manually sharding, it will instead iterate through each shard's guild caches.
</p>

```csharp
public DiscordClient GetShard(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID for the shard.

#### Returns

[DiscordClient](DSharpPlus.DiscordClient.md)

The found <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> shard. Otherwise <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> if the shard was not found for the guild ID.

### <a id="DSharpPlus_DiscordShardedClient_GetShard_DSharpPlus_Entities_DiscordGuild_"></a>GetShard\(DiscordGuild\)

Gets a shard from a guild.
<p>
    If automatically sharding, this will use the <xref href="DSharpPlus.Utilities.GetShardId(System.UInt64%2cSystem.Int32)" data-throw-if-not-resolved="false"></xref> method.
    Otherwise if manually sharding, it will instead iterate through each shard's guild caches.
</p>

```csharp
public DiscordClient GetShard(DiscordGuild guild)
```

#### Parameters

`guild` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

The guild for the shard.

#### Returns

[DiscordClient](DSharpPlus.DiscordClient.md)

The found <xref href="DSharpPlus.DiscordClient" data-throw-if-not-resolved="false"></xref> shard. Otherwise <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> if the shard was not found for the guild.

### <a id="DSharpPlus_DiscordShardedClient_InitializeShardsAsync"></a>InitializeShardsAsync\(\)

```csharp
public Task<int> InitializeShardsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

### <a id="DSharpPlus_DiscordShardedClient_StartAsync"></a>StartAsync\(\)

Initializes and connects all shards.

```csharp
public Task StartAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[AggregateException](https://learn.microsoft.com/dotnet/api/system.aggregateexception)

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

### <a id="DSharpPlus_DiscordShardedClient_StopAsync"></a>StopAsync\(\)

Disconnects and disposes of all shards.

```csharp
public Task StopAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

### <a id="DSharpPlus_DiscordShardedClient_UpdateStatusAsync_DSharpPlus_Entities_DiscordActivity_System_Nullable_DSharpPlus_Entities_UserStatus__System_Nullable_System_DateTimeOffset__"></a>UpdateStatusAsync\(DiscordActivity, UserStatus?, DateTimeOffset?\)

Updates playing statuses on all shards.

```csharp
public Task UpdateStatusAsync(DiscordActivity activity = null, UserStatus? userStatus = null, DateTimeOffset? idleSince = null)
```

#### Parameters

`activity` [DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)

Activity to set.

`userStatus` [UserStatus](DSharpPlus.Entities.UserStatus.md)?

Status of the user.

`idleSince` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Since when is the client performing the specified activity.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

Asynchronous operation.

### <a id="DSharpPlus_DiscordShardedClient_ApplicationCommandPermissionsUpdated"></a>ApplicationCommandPermissionsUpdated

```csharp
public event AsyncEventHandler<DiscordClient, ApplicationCommandPermissionsUpdatedEventArgs> ApplicationCommandPermissionsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ApplicationCommandPermissionsUpdatedEventArgs](DSharpPlus.EventArgs.ApplicationCommandPermissionsUpdatedEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_AutoModerationRuleCreated"></a>AutoModerationRuleCreated

Fired when a new auto-moderation rule is created.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleCreateEventArgs> AutoModerationRuleCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleCreateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_AutoModerationRuleDeleted"></a>AutoModerationRuleDeleted

Fired when an auto-moderation rule is deleted.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleDeleteEventArgs> AutoModerationRuleDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleDeleteEventArgs](DSharpPlus.EventArgs.AutoModerationRuleDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_AutoModerationRuleExecuted"></a>AutoModerationRuleExecuted

Fired when an auto-moderation is executed.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleExecuteEventArgs> AutoModerationRuleExecuted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleExecuteEventArgs](DSharpPlus.EventArgs.AutoModerationRuleExecuteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_AutoModerationRuleUpdated"></a>AutoModerationRuleUpdated

Fired when an auto-moderation rule is updated.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleUpdateEventArgs> AutoModerationRuleUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleUpdateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ChannelCreated"></a>ChannelCreated

Fired when a new channel is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelCreateEventArgs> ChannelCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelCreateEventArgs](DSharpPlus.EventArgs.ChannelCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ChannelDeleted"></a>ChannelDeleted

Fired when a channel is deleted
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelDeleteEventArgs> ChannelDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelDeleteEventArgs](DSharpPlus.EventArgs.ChannelDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ChannelPinsUpdated"></a>ChannelPinsUpdated

Fired whenever a channel's pinned message list is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelPinsUpdateEventArgs> ChannelPinsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelPinsUpdateEventArgs](DSharpPlus.EventArgs.ChannelPinsUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ChannelUpdated"></a>ChannelUpdated

Fired when a channel is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelUpdateEventArgs> ChannelUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelUpdateEventArgs](DSharpPlus.EventArgs.ChannelUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ClientErrored"></a>ClientErrored

Fired whenever an error occurs within an event handler.

```csharp
public event AsyncEventHandler<DiscordClient, ClientErrorEventArgs> ClientErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ClientErrorEventArgs](DSharpPlus.EventArgs.ClientErrorEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ComponentInteractionCreated"></a>ComponentInteractionCreated

Fired when a component is invoked.

```csharp
public event AsyncEventHandler<DiscordClient, ComponentInteractionCreateEventArgs> ComponentInteractionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ContextMenuInteractionCreated"></a>ContextMenuInteractionCreated

Fired when a user uses a context menu.

```csharp
public event AsyncEventHandler<DiscordClient, ContextMenuInteractionCreateEventArgs> ContextMenuInteractionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ContextMenuInteractionCreateEventArgs](DSharpPlus.EventArgs.ContextMenuInteractionCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_DmChannelDeleted"></a>DmChannelDeleted

Fired when a dm channel is deleted
For this Event you need the <xref href="DSharpPlus.DiscordIntents.DirectMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, DmChannelDeleteEventArgs> DmChannelDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [DmChannelDeleteEventArgs](DSharpPlus.EventArgs.DmChannelDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildAuditLogCreated"></a>GuildAuditLogCreated

Fired when a audit log entry is created.

```csharp
public event AsyncEventHandler<DiscordClient, GuildAuditLogCreatedEventArgs> GuildAuditLogCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildAuditLogCreatedEventArgs](DSharpPlus.EventArgs.GuildAuditLogCreatedEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildAvailable"></a>GuildAvailable

Fired when a guild is becoming available.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildCreateEventArgs> GuildAvailable
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildCreateEventArgs](DSharpPlus.EventArgs.GuildCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildBanAdded"></a>GuildBanAdded

Fired when a guild ban gets added
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildModeration" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildBanAddEventArgs> GuildBanAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildBanAddEventArgs](DSharpPlus.EventArgs.GuildBanAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildBanRemoved"></a>GuildBanRemoved

Fired when a guild ban gets removed
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildModeration" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildBanRemoveEventArgs> GuildBanRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildBanRemoveEventArgs](DSharpPlus.EventArgs.GuildBanRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildCreated"></a>GuildCreated

Fired when the user joins a new guild.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildCreateEventArgs> GuildCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildCreateEventArgs](DSharpPlus.EventArgs.GuildCreateEventArgs.md)\>

#### Remarks

[alias="GuildJoined"][alias="JoinedGuild"]

### <a id="DSharpPlus_DiscordShardedClient_GuildDeleted"></a>GuildDeleted

Fired when the user leaves or is removed from a guild.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildDeleteEventArgs> GuildDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildDeleteEventArgs](DSharpPlus.EventArgs.GuildDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildDownloadCompleted"></a>GuildDownloadCompleted

Fired when all guilds finish streaming from Discord.

```csharp
public event AsyncEventHandler<DiscordClient, GuildDownloadCompletedEventArgs> GuildDownloadCompleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildDownloadCompletedEventArgs](DSharpPlus.EventArgs.GuildDownloadCompletedEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildEmojisUpdated"></a>GuildEmojisUpdated

Fired when a guilds emojis get updated
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildEmojisAndStickers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildEmojisUpdateEventArgs> GuildEmojisUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildEmojisUpdateEventArgs](DSharpPlus.EventArgs.GuildEmojisUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildIntegrationsUpdated"></a>GuildIntegrationsUpdated

Fired when a guild integration is updated.

```csharp
public event AsyncEventHandler<DiscordClient, GuildIntegrationsUpdateEventArgs> GuildIntegrationsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildIntegrationsUpdateEventArgs](DSharpPlus.EventArgs.GuildIntegrationsUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildMemberAdded"></a>GuildMemberAdded

Fired when a new user joins a guild.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildMemberAddEventArgs> GuildMemberAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMemberAddEventArgs](DSharpPlus.EventArgs.GuildMemberAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildMemberRemoved"></a>GuildMemberRemoved

Fired when a user is removed from a guild (leave/kick/ban).
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildMemberRemoveEventArgs> GuildMemberRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMemberRemoveEventArgs](DSharpPlus.EventArgs.GuildMemberRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildMemberUpdated"></a>GuildMemberUpdated

Fired when a guild member is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildMemberUpdateEventArgs> GuildMemberUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMemberUpdateEventArgs](DSharpPlus.EventArgs.GuildMemberUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildMembersChunked"></a>GuildMembersChunked

Fired in response to Gateway Request Guild Members.

```csharp
public event AsyncEventHandler<DiscordClient, GuildMembersChunkEventArgs> GuildMembersChunked
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMembersChunkEventArgs](DSharpPlus.EventArgs.GuildMembersChunkEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildRoleCreated"></a>GuildRoleCreated

Fired when a guild role is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildRoleCreateEventArgs> GuildRoleCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildRoleCreateEventArgs](DSharpPlus.EventArgs.GuildRoleCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildRoleDeleted"></a>GuildRoleDeleted

Fired when a guild role is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildRoleDeleteEventArgs> GuildRoleDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildRoleDeleteEventArgs](DSharpPlus.EventArgs.GuildRoleDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildRoleUpdated"></a>GuildRoleUpdated

Fired when a guild role is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildRoleUpdateEventArgs> GuildRoleUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildRoleUpdateEventArgs](DSharpPlus.EventArgs.GuildRoleUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildStickersUpdated"></a>GuildStickersUpdated

```csharp
public event AsyncEventHandler<DiscordClient, GuildStickersUpdateEventArgs> GuildStickersUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildStickersUpdateEventArgs](DSharpPlus.EventArgs.GuildStickersUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildUnavailable"></a>GuildUnavailable

Fired when a guild becomes unavailable.

```csharp
public event AsyncEventHandler<DiscordClient, GuildDeleteEventArgs> GuildUnavailable
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildDeleteEventArgs](DSharpPlus.EventArgs.GuildDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_GuildUpdated"></a>GuildUpdated

Fired when a guild is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildUpdateEventArgs> GuildUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildUpdateEventArgs](DSharpPlus.EventArgs.GuildUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_Heartbeated"></a>Heartbeated

Fired on received heartbeat ACK.

```csharp
public event AsyncEventHandler<DiscordClient, HeartbeatEventArgs> Heartbeated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [HeartbeatEventArgs](DSharpPlus.EventArgs.HeartbeatEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_IntegrationCreated"></a>IntegrationCreated

Fired when an integration is created.

```csharp
public event AsyncEventHandler<DiscordClient, IntegrationCreateEventArgs> IntegrationCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [IntegrationCreateEventArgs](DSharpPlus.EventArgs.IntegrationCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_IntegrationDeleted"></a>IntegrationDeleted

Fired when an integration is deleted.

```csharp
public event AsyncEventHandler<DiscordClient, IntegrationDeleteEventArgs> IntegrationDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [IntegrationDeleteEventArgs](DSharpPlus.EventArgs.IntegrationDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_IntegrationUpdated"></a>IntegrationUpdated

Fired when an integration is updated.

```csharp
public event AsyncEventHandler<DiscordClient, IntegrationUpdateEventArgs> IntegrationUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [IntegrationUpdateEventArgs](DSharpPlus.EventArgs.IntegrationUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_InteractionCreated"></a>InteractionCreated

Fired when an interaction is invoked.

```csharp
public event AsyncEventHandler<DiscordClient, InteractionCreateEventArgs> InteractionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [InteractionCreateEventArgs](DSharpPlus.EventArgs.InteractionCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_InviteCreated"></a>InviteCreated

Fired when an invite is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildInvites" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, InviteCreateEventArgs> InviteCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [InviteCreateEventArgs](DSharpPlus.EventArgs.InviteCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_InviteDeleted"></a>InviteDeleted

Fired when an invite is deleted.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildInvites" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, InviteDeleteEventArgs> InviteDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [InviteDeleteEventArgs](DSharpPlus.EventArgs.InviteDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageAcknowledged"></a>MessageAcknowledged

Fired when message is acknowledged by the user.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageAcknowledgeEventArgs> MessageAcknowledged
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageAcknowledgeEventArgs](DSharpPlus.EventArgs.MessageAcknowledgeEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageCreated"></a>MessageCreated

Fired when a message is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageCreateEventArgs> MessageCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageCreateEventArgs](DSharpPlus.EventArgs.MessageCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageDeleted"></a>MessageDeleted

Fired when a message is deleted.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageDeleteEventArgs> MessageDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageDeleteEventArgs](DSharpPlus.EventArgs.MessageDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageReactionAdded"></a>MessageReactionAdded

Fired when a reaction gets added to a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionAddEventArgs> MessageReactionAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageReactionRemoved"></a>MessageReactionRemoved

Fired when a reaction gets removed from a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionRemoveEventArgs> MessageReactionRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionRemoveEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageReactionRemovedEmoji"></a>MessageReactionRemovedEmoji

Fired when all reactions of a specific reaction are removed from a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionRemoveEmojiEventArgs> MessageReactionRemovedEmoji
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionRemoveEmojiEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEmojiEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageReactionsCleared"></a>MessageReactionsCleared

Fired when all reactions get removed from a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionsClearEventArgs> MessageReactionsCleared
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionsClearEventArgs](DSharpPlus.EventArgs.MessageReactionsClearEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessageUpdated"></a>MessageUpdated

Fired when a message is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageUpdateEventArgs> MessageUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageUpdateEventArgs](DSharpPlus.EventArgs.MessageUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_MessagesBulkDeleted"></a>MessagesBulkDeleted

Fired when multiple messages are deleted at once.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageBulkDeleteEventArgs> MessagesBulkDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageBulkDeleteEventArgs](DSharpPlus.EventArgs.MessageBulkDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ModalSubmitted"></a>ModalSubmitted

Fired when a modal is submitted. If a modal is closed, this event is not fired.

```csharp
public event AsyncEventHandler<DiscordClient, ModalSubmitEventArgs> ModalSubmitted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_PresenceUpdated"></a>PresenceUpdated

Fired when a presence has been updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, PresenceUpdateEventArgs> PresenceUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [PresenceUpdateEventArgs](DSharpPlus.EventArgs.PresenceUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ScheduledGuildEventCompleted"></a>ScheduledGuildEventCompleted

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventCompletedEventArgs> ScheduledGuildEventCompleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventCompletedEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventCompletedEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ScheduledGuildEventCreated"></a>ScheduledGuildEventCreated

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventCreateEventArgs> ScheduledGuildEventCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventCreateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ScheduledGuildEventDeleted"></a>ScheduledGuildEventDeleted

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventDeleteEventArgs> ScheduledGuildEventDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventDeleteEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ScheduledGuildEventUpdated"></a>ScheduledGuildEventUpdated

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventUpdateEventArgs> ScheduledGuildEventUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventUpdateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ScheduledGuildEventUserAdded"></a>ScheduledGuildEventUserAdded

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventUserAddEventArgs> ScheduledGuildEventUserAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventUserAddEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ScheduledGuildEventUserRemoved"></a>ScheduledGuildEventUserRemoved

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventUserRemoveEventArgs> ScheduledGuildEventUserRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventUserRemoveEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_SessionCreated"></a>SessionCreated

Fired when this client has successfully completed its handshake with the websocket gateway.

```csharp
public event AsyncEventHandler<DiscordClient, SessionReadyEventArgs> SessionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SessionReadyEventArgs](DSharpPlus.EventArgs.SessionReadyEventArgs.md)\>

#### Remarks

<i>
  <xref href="DSharpPlus.DiscordClient.Guilds" data-throw-if-not-resolved="false"></xref> will not be populated when this event is fired.</i>
<br />
    See also: <xref href="DSharpPlus.DiscordClient.GuildAvailable" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildDownloadCompleted" data-throw-if-not-resolved="false"></xref>

### <a id="DSharpPlus_DiscordShardedClient_SessionResumed"></a>SessionResumed

Fired whenever a session is resumed.

```csharp
public event AsyncEventHandler<DiscordClient, SessionReadyEventArgs> SessionResumed
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SessionReadyEventArgs](DSharpPlus.EventArgs.SessionReadyEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_SocketClosed"></a>SocketClosed

Fired whenever WebSocket connection is terminated.

```csharp
public event AsyncEventHandler<DiscordClient, SocketCloseEventArgs> SocketClosed
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SocketCloseEventArgs](DSharpPlus.EventArgs.SocketCloseEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_SocketErrored"></a>SocketErrored

Fired whenever a WebSocket error occurs within the client.

```csharp
public event AsyncEventHandler<DiscordClient, SocketErrorEventArgs> SocketErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SocketErrorEventArgs](DSharpPlus.EventArgs.SocketErrorEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_SocketOpened"></a>SocketOpened

Fired whenever WebSocket connection is established.

```csharp
public event AsyncEventHandler<DiscordClient, SocketEventArgs> SocketOpened
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SocketEventArgs](DSharpPlus.EventArgs.SocketEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_StageInstanceCreated"></a>StageInstanceCreated

Fired when a stage instance is created.

```csharp
public event AsyncEventHandler<DiscordClient, StageInstanceCreateEventArgs> StageInstanceCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [StageInstanceCreateEventArgs](DSharpPlus.EventArgs.StageInstanceCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_StageInstanceDeleted"></a>StageInstanceDeleted

Fired when a stage instance is deleted.

```csharp
public event AsyncEventHandler<DiscordClient, StageInstanceDeleteEventArgs> StageInstanceDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [StageInstanceDeleteEventArgs](DSharpPlus.EventArgs.StageInstanceDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_StageInstanceUpdated"></a>StageInstanceUpdated

Fired when a stage instance is updated.

```csharp
public event AsyncEventHandler<DiscordClient, StageInstanceUpdateEventArgs> StageInstanceUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [StageInstanceUpdateEventArgs](DSharpPlus.EventArgs.StageInstanceUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ThreadCreated"></a>ThreadCreated

Fired when a thread is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadCreateEventArgs> ThreadCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadCreateEventArgs](DSharpPlus.EventArgs.ThreadCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ThreadDeleted"></a>ThreadDeleted

Fired when a thread is deleted.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadDeleteEventArgs> ThreadDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadDeleteEventArgs](DSharpPlus.EventArgs.ThreadDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ThreadListSynced"></a>ThreadListSynced

Fired when the current member gains access to a channel(s) that has threads.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadListSyncEventArgs> ThreadListSynced
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadListSyncEventArgs](DSharpPlus.EventArgs.ThreadListSyncEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ThreadMemberUpdated"></a>ThreadMemberUpdated

Fired when the thread member for the current user is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadMemberUpdateEventArgs> ThreadMemberUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadMemberUpdateEventArgs](DSharpPlus.EventArgs.ThreadMemberUpdateEventArgs.md)\>

#### Remarks

This event is mostly documented for completeness, and it not fired every time
DM channels in which no prior messages were received or sent.

### <a id="DSharpPlus_DiscordShardedClient_ThreadMembersUpdated"></a>ThreadMembersUpdated

Fired when the thread members are updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadMembersUpdateEventArgs> ThreadMembersUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadMembersUpdateEventArgs](DSharpPlus.EventArgs.ThreadMembersUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_ThreadUpdated"></a>ThreadUpdated

Fired when a thread is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadUpdateEventArgs> ThreadUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadUpdateEventArgs](DSharpPlus.EventArgs.ThreadUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_TypingStarted"></a>TypingStarted

Fired when a user starts typing in a channel.

```csharp
public event AsyncEventHandler<DiscordClient, TypingStartEventArgs> TypingStarted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_UnknownEvent"></a>UnknownEvent

Fired when an unknown event gets received.

```csharp
public event AsyncEventHandler<DiscordClient, UnknownEventArgs> UnknownEvent
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [UnknownEventArgs](DSharpPlus.EventArgs.UnknownEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_UserSettingsUpdated"></a>UserSettingsUpdated

Fired when the current user updates their settings.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, UserSettingsUpdateEventArgs> UserSettingsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [UserSettingsUpdateEventArgs](DSharpPlus.EventArgs.UserSettingsUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_UserUpdated"></a>UserUpdated

Fired when properties about the current user change.

```csharp
public event AsyncEventHandler<DiscordClient, UserUpdateEventArgs> UserUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [UserUpdateEventArgs](DSharpPlus.EventArgs.UserUpdateEventArgs.md)\>

#### Remarks

NB: This event only applies for changes to the <b>current user</b>, the client that is connected to Discord.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

### <a id="DSharpPlus_DiscordShardedClient_VoiceServerUpdated"></a>VoiceServerUpdated

Fired when a guild's voice server is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildVoiceStates" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, VoiceServerUpdateEventArgs> VoiceServerUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [VoiceServerUpdateEventArgs](DSharpPlus.EventArgs.VoiceServerUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_VoiceStateUpdated"></a>VoiceStateUpdated

Fired when someone joins/leaves/moves voice channels.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildVoiceStates" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, VoiceStateUpdateEventArgs> VoiceStateUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [VoiceStateUpdateEventArgs](DSharpPlus.EventArgs.VoiceStateUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_WebhooksUpdated"></a>WebhooksUpdated

Fired whenever webhooks update.

```csharp
public event AsyncEventHandler<DiscordClient, WebhooksUpdateEventArgs> WebhooksUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [WebhooksUpdateEventArgs](DSharpPlus.EventArgs.WebhooksUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordShardedClient_Zombied"></a>Zombied

Fired on heartbeat attempt cancellation due to too many failed heartbeats.

```csharp
public event AsyncEventHandler<DiscordClient, ZombiedEventArgs> Zombied
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ZombiedEventArgs](DSharpPlus.EventArgs.ZombiedEventArgs.md)\>

