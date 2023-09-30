# Class DiscordClient

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

A Discord API wrapper.

```csharp
public sealed class DiscordClient : BaseDiscordClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseDiscordClient](DSharpPlus.BaseDiscordClient.md) ← 
[DiscordClient](DSharpPlus.DiscordClient.md)

###### Inherited Members

[BaseDiscordClient.Logger](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_Logger), 
[BaseDiscordClient.VersionString](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_VersionString), 
[BaseDiscordClient.CurrentUser](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_CurrentUser), 
[BaseDiscordClient.CurrentApplication](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_CurrentApplication), 
[BaseDiscordClient.Guilds](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_Guilds), 
[BaseDiscordClient.VoiceRegions](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_VoiceRegions), 
[BaseDiscordClient.GetCurrentApplicationAsync\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_GetCurrentApplicationAsync), 
[BaseDiscordClient.ListVoiceRegionsAsync\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_ListVoiceRegionsAsync), 
[BaseDiscordClient.InitializeAsync\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_InitializeAsync), 
[BaseDiscordClient.GetGatewayInfoAsync\(string\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_GetGatewayInfoAsync\_System\_String\_), 
[BaseDiscordClient.Dispose\(\)](DSharpPlus.BaseDiscordClient.md\#DSharpPlus\_BaseDiscordClient\_Dispose)

###### Extension Methods

[ExtensionMethods.GetCommandsNext\(DiscordClient\)](DSharpPlus.CommandsNext.ExtensionMethods.md\#DSharpPlus\_CommandsNext\_ExtensionMethods\_GetCommandsNext\_DSharpPlus\_DiscordClient\_), 
[ClientExtensions.GetInteractivity\(DiscordClient\)](DSharpPlus.Interactivity.Extensions.ClientExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ClientExtensions\_GetInteractivity\_DSharpPlus\_DiscordClient\_), 
[DiscordClientExtensions.GetLavalink\(DiscordClient\)](DSharpPlus.Lavalink.DiscordClientExtensions.md\#DSharpPlus\_Lavalink\_DiscordClientExtensions\_GetLavalink\_DSharpPlus\_DiscordClient\_), 
[ExtensionMethods.GetSlashCommands\(DiscordClient\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetSlashCommands\_DSharpPlus\_DiscordClient\_), 
[DiscordClientExtensions.GetVoiceNext\(DiscordClient\)](DSharpPlus.VoiceNext.DiscordClientExtensions.md\#DSharpPlus\_VoiceNext\_DiscordClientExtensions\_GetVoiceNext\_DSharpPlus\_DiscordClient\_), 
[ExtensionMethods.UseCommandsNext\(DiscordClient, CommandsNextConfiguration\)](DSharpPlus.CommandsNext.ExtensionMethods.md\#DSharpPlus\_CommandsNext\_ExtensionMethods\_UseCommandsNext\_DSharpPlus\_DiscordClient\_DSharpPlus\_CommandsNext\_CommandsNextConfiguration\_), 
[ClientExtensions.UseInteractivity\(DiscordClient, InteractivityConfiguration\)](DSharpPlus.Interactivity.Extensions.ClientExtensions.md\#DSharpPlus\_Interactivity\_Extensions\_ClientExtensions\_UseInteractivity\_DSharpPlus\_DiscordClient\_DSharpPlus\_Interactivity\_InteractivityConfiguration\_), 
[DiscordClientExtensions.UseLavalink\(DiscordClient\)](DSharpPlus.Lavalink.DiscordClientExtensions.md\#DSharpPlus\_Lavalink\_DiscordClientExtensions\_UseLavalink\_DSharpPlus\_DiscordClient\_), 
[ExtensionMethods.UseSlashCommands\(DiscordClient, SlashCommandsConfiguration\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_UseSlashCommands\_DSharpPlus\_DiscordClient\_DSharpPlus\_SlashCommands\_SlashCommandsConfiguration\_), 
[DiscordClientExtensions.UseVoiceNext\(DiscordClient\)](DSharpPlus.VoiceNext.DiscordClientExtensions.md\#DSharpPlus\_VoiceNext\_DiscordClientExtensions\_UseVoiceNext\_DSharpPlus\_DiscordClient\_), 
[DiscordClientExtensions.UseVoiceNext\(DiscordClient, VoiceNextConfiguration\)](DSharpPlus.VoiceNext.DiscordClientExtensions.md\#DSharpPlus\_VoiceNext\_DiscordClientExtensions\_UseVoiceNext\_DSharpPlus\_DiscordClient\_DSharpPlus\_VoiceNext\_VoiceNextConfiguration\_)

## Constructors

### <a id="DSharpPlus_DiscordClient__ctor_DSharpPlus_DiscordConfiguration_"></a>DiscordClient\(DiscordConfiguration\)

Initializes a new instance of DiscordClient.

```csharp
public DiscordClient(DiscordConfiguration config)
```

#### Parameters

`config` [DiscordConfiguration](DSharpPlus.DiscordConfiguration.md)

Specifies configuration parameters.

## Properties

### <a id="DSharpPlus_DiscordClient_GatewayInfo"></a>GatewayInfo

Gets the gateway session information for this client.

```csharp
public GatewayInfo GatewayInfo { get; }
```

#### Property Value

[GatewayInfo](DSharpPlus.Net.GatewayInfo.md)

### <a id="DSharpPlus_DiscordClient_GatewayUri"></a>GatewayUri

Gets the gateway URL.

```csharp
public Uri GatewayUri { get; }
```

#### Property Value

[Uri](https://learn.microsoft.com/dotnet/api/system.uri)

### <a id="DSharpPlus_DiscordClient_GatewayVersion"></a>GatewayVersion

Gets the gateway protocol version.

```csharp
public int GatewayVersion { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_DiscordClient_Guilds"></a>Guilds

Gets a dictionary of guilds that this client is in. The dictionary's key is the guild ID. Note that the
guild objects in this dictionary will not be filled in if the specific guilds aren't available (the
<xref href="DSharpPlus.DiscordClient.GuildAvailable" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordClient.GuildDownloadCompleted" data-throw-if-not-resolved="false"></xref> events haven't been fired yet)

```csharp
public override IReadOnlyDictionary<ulong, DiscordGuild> Guilds { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

### <a id="DSharpPlus_DiscordClient_Intents"></a>Intents

Gets the intents configured for this client.

```csharp
public DiscordIntents Intents { get; }
```

#### Property Value

[DiscordIntents](DSharpPlus.DiscordIntents.md)

### <a id="DSharpPlus_DiscordClient_Ping"></a>Ping

Gets the WS latency for this client.

```csharp
public int Ping { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_DiscordClient_Presences"></a>Presences

Gets the collection of presences held by this client.

```csharp
public IReadOnlyDictionary<ulong, DiscordPresence> Presences { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordPresence](DSharpPlus.Entities.DiscordPresence.md)\>

### <a id="DSharpPlus_DiscordClient_PrivateChannels"></a>PrivateChannels

Gets a dictionary of DM channels that have been cached by this client. The dictionary's key is the channel
ID.

```csharp
public IReadOnlyDictionary<ulong, DiscordDmChannel> PrivateChannels { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

### <a id="DSharpPlus_DiscordClient_ShardCount"></a>ShardCount

Gets the total number of shards the bot is connected to.

```csharp
public int ShardCount { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

### <a id="DSharpPlus_DiscordClient_ShardId"></a>ShardId

Gets the currently connected shard ID.

```csharp
public int ShardId { get; }
```

#### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### <a id="DSharpPlus_DiscordClient_AddExtension_DSharpPlus_BaseExtension_"></a>AddExtension\(BaseExtension\)

Registers an extension with this client.

```csharp
public void AddExtension(BaseExtension ext)
```

#### Parameters

`ext` [BaseExtension](DSharpPlus.BaseExtension.md)

Extension to register.

### <a id="DSharpPlus_DiscordClient_BulkOverwriteGlobalApplicationCommandsAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommand__"></a>BulkOverwriteGlobalApplicationCommandsAsync\(IEnumerable<DiscordApplicationCommand\>\)

Overwrites the existing global application commands. New commands are automatically created and missing commands are automatically deleted.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> BulkOverwriteGlobalApplicationCommandsAsync(IEnumerable<DiscordApplicationCommand> commands)
```

#### Parameters

`commands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The list of commands to overwrite with.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

The list of global commands.

### <a id="DSharpPlus_DiscordClient_BulkOverwriteGuildApplicationCommandsAsync_System_UInt64_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordApplicationCommand__"></a>BulkOverwriteGuildApplicationCommandsAsync\(ulong, IEnumerable<DiscordApplicationCommand\>\)

Overwrites the existing application commands in a guild. New commands are automatically created and missing commands are automatically deleted.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> BulkOverwriteGuildApplicationCommandsAsync(ulong guildId, IEnumerable<DiscordApplicationCommand> commands)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`commands` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The list of commands to overwrite with.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

The list of guild commands.

### <a id="DSharpPlus_DiscordClient_ConnectAsync_DSharpPlus_Entities_DiscordActivity_System_Nullable_DSharpPlus_Entities_UserStatus__System_Nullable_System_DateTimeOffset__"></a>ConnectAsync\(DiscordActivity, UserStatus?, DateTimeOffset?\)

Connects to the gateway

```csharp
public Task ConnectAsync(DiscordActivity activity = null, UserStatus? status = null, DateTimeOffset? idlesince = null)
```

#### Parameters

`activity` [DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)

`status` [UserStatus](DSharpPlus.Entities.UserStatus.md)?

`idlesince` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when an invalid token was provided.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_CreateGlobalApplicationCommandAsync_DSharpPlus_Entities_DiscordApplicationCommand_"></a>CreateGlobalApplicationCommandAsync\(DiscordApplicationCommand\)

Creates or overwrites a global application command.

```csharp
public Task<DiscordApplicationCommand> CreateGlobalApplicationCommandAsync(DiscordApplicationCommand command)
```

#### Parameters

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to create.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The created command.

### <a id="DSharpPlus_DiscordClient_CreateGuildApplicationCommandAsync_System_UInt64_DSharpPlus_Entities_DiscordApplicationCommand_"></a>CreateGuildApplicationCommandAsync\(ulong, DiscordApplicationCommand\)

Creates or overwrites a guild application command.

```csharp
public Task<DiscordApplicationCommand> CreateGuildApplicationCommandAsync(ulong guildId, DiscordApplicationCommand command)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to create the application command in.

`command` [DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)

The command to create.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The created command.

### <a id="DSharpPlus_DiscordClient_CreateGuildAsync_System_String_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__System_Nullable_DSharpPlus_Entities_VerificationLevel__System_Nullable_DSharpPlus_Entities_DefaultMessageNotifications__System_Nullable_DSharpPlus_SystemChannelFlags__"></a>CreateGuildAsync\(string, string, Optional<Stream\>, VerificationLevel?, DefaultMessageNotifications?, SystemChannelFlags?\)

Creates a guild. This requires the bot to be in less than 10 guilds total.

```csharp
public Task<DiscordGuild> CreateGuildAsync(string name, string region = null, Optional<Stream> icon = default, VerificationLevel? verificationLevel = null, DefaultMessageNotifications? defaultMessageNotifications = null, SystemChannelFlags? systemChannelFlags = null)
```

#### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the guild.

`region` [string](https://learn.microsoft.com/dotnet/api/system.string)

Voice region of the guild.

`icon` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Stream containing the icon for the guild.

`verificationLevel` [VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)?

Verification level for the guild.

`defaultMessageNotifications` [DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)?

Default message notification settings for the guild.

`systemChannelFlags` [SystemChannelFlags](DSharpPlus.SystemChannelFlags.md)?

System channel flags fopr the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The created guild.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_CreateGuildFromTemplateAsync_System_String_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__"></a>CreateGuildFromTemplateAsync\(string, string, Optional<Stream\>\)

Creates a guild from a template. This requires the bot to be in less than 10 guilds total.

```csharp
public Task<DiscordGuild> CreateGuildFromTemplateAsync(string code, string name, Optional<Stream> icon = default)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the guild.

`icon` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

Stream containing the icon for the guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The created guild.

#### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_DeleteGlobalApplicationCommandAsync_System_UInt64_"></a>DeleteGlobalApplicationCommandAsync\(ulong\)

Deletes a global application command.

```csharp
public Task DeleteGlobalApplicationCommandAsync(ulong commandId)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to delete.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordClient_DeleteGuildApplicationCommandAsync_System_UInt64_System_UInt64_"></a>DeleteGuildApplicationCommandAsync\(ulong, ulong\)

Deletes a application command in a guild.

```csharp
public Task DeleteGuildApplicationCommandAsync(ulong guildId, ulong commandId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to delete the application command in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordClient_DisconnectAsync"></a>DisconnectAsync\(\)

Disconnects from the gateway

```csharp
public Task DisconnectAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordClient_Dispose"></a>Dispose\(\)

Disposes your DiscordClient.

```csharp
public override void Dispose()
```

### <a id="DSharpPlus_DiscordClient_EditGlobalApplicationCommandAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_ApplicationCommandEditModel__"></a>EditGlobalApplicationCommandAsync\(ulong, Action<ApplicationCommandEditModel\>\)

Edits a global application command.

```csharp
public Task<DiscordApplicationCommand> EditGlobalApplicationCommandAsync(ulong commandId, Action<ApplicationCommandEditModel> action)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)\>

Action to perform.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The edited command.

### <a id="DSharpPlus_DiscordClient_EditGuildApplicationCommandAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_ApplicationCommandEditModel__"></a>EditGuildApplicationCommandAsync\(ulong, ulong, Action<ApplicationCommandEditModel\>\)

Edits a application command in a guild.

```csharp
public Task<DiscordApplicationCommand> EditGuildApplicationCommandAsync(ulong guildId, ulong commandId, Action<ApplicationCommandEditModel> action)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the application command is in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to edit.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ApplicationCommandEditModel](DSharpPlus.Net.Models.ApplicationCommandEditModel.md)\>

Action to perform.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The edited command.

### <a id="DSharpPlus_DiscordClient_GetChannelAsync_System_UInt64_"></a>GetChannelAsync\(ulong\)

Gets a channel

```csharp
public Task<DiscordChannel> GetChannelAsync(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetConnectionsAsync"></a>GetConnectionsAsync\(\)

Gets a list of connections

```csharp
public Task<IReadOnlyList<DiscordConnection>> GetConnectionsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordConnection](DSharpPlus.Entities.DiscordConnection.md)\>\>

#### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetExtension__1"></a>GetExtension<T\>\(\)

Retrieves a previously-registered extension from this client.

```csharp
public T GetExtension<T>() where T : BaseExtension
```

#### Returns

T

The requested extension.

#### Type Parameters

`T` 

Type of extension to retrieve.

### <a id="DSharpPlus_DiscordClient_GetGlobalApplicationCommandAsync_System_UInt64_"></a>GetGlobalApplicationCommandAsync\(ulong\)

Gets a global application command by its id.

```csharp
public Task<DiscordApplicationCommand> GetGlobalApplicationCommandAsync(ulong commandId)
```

#### Parameters

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

### <a id="DSharpPlus_DiscordClient_GetGlobalApplicationCommandAsync_System_String_"></a>GetGlobalApplicationCommandAsync\(string\)

Gets a global application command by its name.

```csharp
public Task<DiscordApplicationCommand> GetGlobalApplicationCommandAsync(string commandName)
```

#### Parameters

`commandName` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the command to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the name.

### <a id="DSharpPlus_DiscordClient_GetGlobalApplicationCommandsAsync"></a>GetGlobalApplicationCommandsAsync\(\)

Gets all the global application commands for this application.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> GetGlobalApplicationCommandsAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

A list of global application commands.

### <a id="DSharpPlus_DiscordClient_GetGuildApplicationCommandAsync_System_UInt64_System_UInt64_"></a>GetGuildApplicationCommandAsync\(ulong, ulong\)

Gets a application command in a guild by its ID.

```csharp
public Task<DiscordApplicationCommand> GetGuildApplicationCommandAsync(ulong guildId, ulong commandId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild the application command is in.

`commandId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the command to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>

The command with the ID.

### <a id="DSharpPlus_DiscordClient_GetGuildApplicationCommandsAsync_System_UInt64_"></a>GetGuildApplicationCommandsAsync\(ulong\)

Gets all the application commands for a guild.

```csharp
public Task<IReadOnlyList<DiscordApplicationCommand>> GetGuildApplicationCommandsAsync(ulong guildId)
```

#### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to get application commands for.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordApplicationCommand](DSharpPlus.Entities.DiscordApplicationCommand.md)\>\>

A list of application commands in the guild.

### <a id="DSharpPlus_DiscordClient_GetGuildAsync_System_UInt64_System_Nullable_System_Boolean__"></a>GetGuildAsync\(ulong, bool?\)

Gets a guild.
<p>Setting <code class="paramref">withCounts</code> to true will make a REST request.</p>

```csharp
public Task<DiscordGuild> GetGuildAsync(ulong id, bool? withCounts = null)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID to search for.

`withCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include approximate presence and member counts in the returned guild.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The requested Guild.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetGuildPreviewAsync_System_UInt64_"></a>GetGuildPreviewAsync\(ulong\)

Gets a guild preview

```csharp
public Task<DiscordGuildPreview> GetGuildPreviewAsync(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildPreview](DSharpPlus.Entities.DiscordGuildPreview.md)\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetInviteByCodeAsync_System_String_System_Nullable_System_Boolean__System_Nullable_System_Boolean__"></a>GetInviteByCodeAsync\(string, bool?, bool?\)

Gets an invite.

```csharp
public Task<DiscordInvite> GetInviteByCodeAsync(string code, bool? withCounts = null, bool? withExpiration = null)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The invite code.

`withCounts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include presence and total member counts in the returned invite.

`withExpiration` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include the expiration date in the returned invite.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

The requested Invite.

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the invite does not exists.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetStickerAsync_System_UInt64_"></a>GetStickerAsync\(ulong\)

Gets a sticker.

```csharp
public Task<DiscordMessageSticker> GetStickerAsync(ulong stickerId)
```

#### Parameters

`stickerId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the sticker.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

The specified sticker

### <a id="DSharpPlus_DiscordClient_GetStickerPacksAsync"></a>GetStickerPacksAsync\(\)

Gets a collection of sticker packs that may be used by nitro users.

```csharp
public Task<IReadOnlyList<DiscordMessageStickerPack>> GetStickerPacksAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageStickerPack](DSharpPlus.Entities.DiscordMessageStickerPack.md)\>\>

### <a id="DSharpPlus_DiscordClient_GetTemplateAsync_System_String_"></a>GetTemplateAsync\(string\)

Gets a guild template by the code.

```csharp
public Task<DiscordGuildTemplate> GetTemplateAsync(string code)
```

#### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The guild template for the code.

#### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetUserAsync_System_UInt64_System_Boolean_"></a>GetUserAsync\(ulong, bool\)

Gets a user

```csharp
public Task<DiscordUser> GetUserAsync(ulong userId, bool updateCache = false)
```

#### Parameters

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the user

`updateCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request and update cache. Passing true will update the user, updating stale properties such as <xref href="DSharpPlus.Entities.DiscordUser.BannerHash" data-throw-if-not-resolved="false"></xref>.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

#### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetWebhookAsync_System_UInt64_"></a>GetWebhookAsync\(ulong\)

Gets a webhook

```csharp
public Task<DiscordWebhook> GetWebhookAsync(ulong id)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of webhook to get.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_GetWebhookWithTokenAsync_System_UInt64_System_String_"></a>GetWebhookWithTokenAsync\(ulong, string\)

Gets a webhook

```csharp
public Task<DiscordWebhook> GetWebhookWithTokenAsync(ulong id, string token)
```

#### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of webhook to get.

`token` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordWebhook](DSharpPlus.Entities.DiscordWebhook.md)\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the webhook does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_ReconnectAsync_System_Boolean_"></a>ReconnectAsync\(bool\)

```csharp
public Task ReconnectAsync(bool startNewSession = false)
```

#### Parameters

`startNewSession` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_System_String_"></a>SendMessageAsync\(DiscordChannel, string\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, string content)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message content to send.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordChannel, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, DiscordEmbed embed)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>SendMessageAsync\(DiscordChannel, string, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, string content, DiscordEmbed embed)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message content to send.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach to the message.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Entities_DiscordMessageBuilder_"></a>SendMessageAsync\(DiscordChannel, DiscordMessageBuilder\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, DiscordMessageBuilder builder)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The Discord Message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is false and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_SendMessageAsync_DSharpPlus_Entities_DiscordChannel_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>SendMessageAsync\(DiscordChannel, Action<DiscordMessageBuilder\>\)

Sends a message

```csharp
public Task<DiscordMessage> SendMessageAsync(DiscordChannel channel, Action<DiscordMessageBuilder> action)
```

#### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to send to.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The Discord Message builder.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The Discord Message that was sent.

#### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref> permission if TTS is false and <xref href="DSharpPlus.Permissions.SendTtsMessages" data-throw-if-not-resolved="false"></xref> if TTS is true.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_SendPayloadAsync__1_DSharpPlus_Net_Abstractions_GatewayOpCode___0_"></a>SendPayloadAsync<T\>\(GatewayOpCode, T\)

Sends a raw payload to the gateway. This method is not recommended for use unless you know what you're doing.

```csharp
[Obsolete("This method should not be used unless you know what you're doing. Instead, look towards the other explicitly implemented methods which come with client-side validation.")]
public Task SendPayloadAsync<T>(GatewayOpCode opCode, T data)
```

#### Parameters

`opCode` [GatewayOpCode](DSharpPlus.Net.Abstractions.GatewayOpCode.md)

The opcode to send to the Discord gateway.

`data` T

The data to deserialize.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the payload being sent.

#### Type Parameters

`T` 

The type of data that the object belongs to.

### <a id="DSharpPlus_DiscordClient_SendPayloadAsync_DSharpPlus_Net_Abstractions_GatewayOpCode_System_Object_"></a>SendPayloadAsync\(GatewayOpCode, object?\)

Sends a raw payload to the gateway. This method is not recommended for use unless you know what you're doing.

```csharp
[Obsolete("This method should not be used unless you know what you're doing. Instead, look towards the other explicitly implemented methods which come with client-side validation.")]
public Task SendPayloadAsync(GatewayOpCode opCode, object? data = null)
```

#### Parameters

`opCode` [GatewayOpCode](DSharpPlus.Net.Abstractions.GatewayOpCode.md)

The opcode to send to the Discord gateway.

`data` [object](https://learn.microsoft.com/dotnet/api/system.object)?

The data to deserialize.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the payload being sent.

### <a id="DSharpPlus_DiscordClient_UpdateCurrentUserAsync_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__"></a>UpdateCurrentUserAsync\(string, Optional<Stream\>\)

Edits current user.

```csharp
public Task<DiscordUser> UpdateCurrentUserAsync(string username = null, Optional<Stream> avatar = default)
```

#### Parameters

`username` [string](https://learn.microsoft.com/dotnet/api/system.string)

New username.

`avatar` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

New avatar.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

#### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the user does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

### <a id="DSharpPlus_DiscordClient_UpdateStatusAsync_DSharpPlus_Entities_DiscordActivity_System_Nullable_DSharpPlus_Entities_UserStatus__System_Nullable_System_DateTimeOffset__"></a>UpdateStatusAsync\(DiscordActivity, UserStatus?, DateTimeOffset?\)

Updates current user's activity and status.

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

### <a id="DSharpPlus_DiscordClient_ApplicationCommandPermissionsUpdated"></a>ApplicationCommandPermissionsUpdated

```csharp
public event AsyncEventHandler<DiscordClient, ApplicationCommandPermissionsUpdatedEventArgs> ApplicationCommandPermissionsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ApplicationCommandPermissionsUpdatedEventArgs](DSharpPlus.EventArgs.ApplicationCommandPermissionsUpdatedEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_AutoModerationRuleCreated"></a>AutoModerationRuleCreated

Fired when a new auto-moderation rule is created.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleCreateEventArgs> AutoModerationRuleCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleCreateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_AutoModerationRuleDeleted"></a>AutoModerationRuleDeleted

Fired when an auto-moderation rule is deleted.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleDeleteEventArgs> AutoModerationRuleDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleDeleteEventArgs](DSharpPlus.EventArgs.AutoModerationRuleDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_AutoModerationRuleExecuted"></a>AutoModerationRuleExecuted

Fired when an auto-moderation is executed.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleExecuteEventArgs> AutoModerationRuleExecuted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleExecuteEventArgs](DSharpPlus.EventArgs.AutoModerationRuleExecuteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_AutoModerationRuleUpdated"></a>AutoModerationRuleUpdated

Fired when an auto-moderation rule is updated.

```csharp
public event AsyncEventHandler<DiscordClient, AutoModerationRuleUpdateEventArgs> AutoModerationRuleUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [AutoModerationRuleUpdateEventArgs](DSharpPlus.EventArgs.AutoModerationRuleUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ChannelCreated"></a>ChannelCreated

Fired when a new channel is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelCreateEventArgs> ChannelCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelCreateEventArgs](DSharpPlus.EventArgs.ChannelCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ChannelDeleted"></a>ChannelDeleted

Fired when a channel is deleted
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelDeleteEventArgs> ChannelDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelDeleteEventArgs](DSharpPlus.EventArgs.ChannelDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ChannelPinsUpdated"></a>ChannelPinsUpdated

Fired whenever a channel's pinned message list is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelPinsUpdateEventArgs> ChannelPinsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelPinsUpdateEventArgs](DSharpPlus.EventArgs.ChannelPinsUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ChannelUpdated"></a>ChannelUpdated

Fired when a channel is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ChannelUpdateEventArgs> ChannelUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ChannelUpdateEventArgs](DSharpPlus.EventArgs.ChannelUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ClientErrored"></a>ClientErrored

Fired whenever an error occurs within an event handler.

```csharp
public event AsyncEventHandler<DiscordClient, ClientErrorEventArgs> ClientErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ClientErrorEventArgs](DSharpPlus.EventArgs.ClientErrorEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ComponentInteractionCreated"></a>ComponentInteractionCreated

Fired when a component is invoked.

```csharp
public event AsyncEventHandler<DiscordClient, ComponentInteractionCreateEventArgs> ComponentInteractionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ComponentInteractionCreateEventArgs](DSharpPlus.EventArgs.ComponentInteractionCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ContextMenuInteractionCreated"></a>ContextMenuInteractionCreated

Fired when a user uses a context menu.

```csharp
public event AsyncEventHandler<DiscordClient, ContextMenuInteractionCreateEventArgs> ContextMenuInteractionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ContextMenuInteractionCreateEventArgs](DSharpPlus.EventArgs.ContextMenuInteractionCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_DmChannelDeleted"></a>DmChannelDeleted

Fired when a dm channel is deleted
For this Event you need the <xref href="DSharpPlus.DiscordIntents.DirectMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, DmChannelDeleteEventArgs> DmChannelDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [DmChannelDeleteEventArgs](DSharpPlus.EventArgs.DmChannelDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildAuditLogCreated"></a>GuildAuditLogCreated

Fired when a audit log entry is created.

```csharp
public event AsyncEventHandler<DiscordClient, GuildAuditLogCreatedEventArgs> GuildAuditLogCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildAuditLogCreatedEventArgs](DSharpPlus.EventArgs.GuildAuditLogCreatedEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildAvailable"></a>GuildAvailable

Fired when a guild is becoming available.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildCreateEventArgs> GuildAvailable
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildCreateEventArgs](DSharpPlus.EventArgs.GuildCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildBanAdded"></a>GuildBanAdded

Fired when a guild ban gets added
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildModeration" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildBanAddEventArgs> GuildBanAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildBanAddEventArgs](DSharpPlus.EventArgs.GuildBanAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildBanRemoved"></a>GuildBanRemoved

Fired when a guild ban gets removed
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildModeration" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildBanRemoveEventArgs> GuildBanRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildBanRemoveEventArgs](DSharpPlus.EventArgs.GuildBanRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildCreated"></a>GuildCreated

Fired when the user joins a new guild.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildCreateEventArgs> GuildCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildCreateEventArgs](DSharpPlus.EventArgs.GuildCreateEventArgs.md)\>

#### Remarks

[alias="GuildJoined"][alias="JoinedGuild"]

### <a id="DSharpPlus_DiscordClient_GuildDeleted"></a>GuildDeleted

Fired when the user leaves or is removed from a guild.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildDeleteEventArgs> GuildDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildDeleteEventArgs](DSharpPlus.EventArgs.GuildDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildDownloadCompleted"></a>GuildDownloadCompleted

Fired when all guilds finish streaming from Discord.

```csharp
public event AsyncEventHandler<DiscordClient, GuildDownloadCompletedEventArgs> GuildDownloadCompleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildDownloadCompletedEventArgs](DSharpPlus.EventArgs.GuildDownloadCompletedEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildEmojisUpdated"></a>GuildEmojisUpdated

Fired when a guilds emojis get updated
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildEmojisAndStickers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildEmojisUpdateEventArgs> GuildEmojisUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildEmojisUpdateEventArgs](DSharpPlus.EventArgs.GuildEmojisUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildIntegrationsUpdated"></a>GuildIntegrationsUpdated

Fired when a guild integration is updated.

```csharp
public event AsyncEventHandler<DiscordClient, GuildIntegrationsUpdateEventArgs> GuildIntegrationsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildIntegrationsUpdateEventArgs](DSharpPlus.EventArgs.GuildIntegrationsUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildMemberAdded"></a>GuildMemberAdded

Fired when a new user joins a guild.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildMemberAddEventArgs> GuildMemberAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMemberAddEventArgs](DSharpPlus.EventArgs.GuildMemberAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildMemberRemoved"></a>GuildMemberRemoved

Fired when a user is removed from a guild (leave/kick/ban).
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildMemberRemoveEventArgs> GuildMemberRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMemberRemoveEventArgs](DSharpPlus.EventArgs.GuildMemberRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildMemberUpdated"></a>GuildMemberUpdated

Fired when a guild member is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildMemberUpdateEventArgs> GuildMemberUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMemberUpdateEventArgs](DSharpPlus.EventArgs.GuildMemberUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildMembersChunked"></a>GuildMembersChunked

Fired in response to Gateway Request Guild Members.

```csharp
public event AsyncEventHandler<DiscordClient, GuildMembersChunkEventArgs> GuildMembersChunked
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMembersChunkEventArgs](DSharpPlus.EventArgs.GuildMembersChunkEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildRoleCreated"></a>GuildRoleCreated

Fired when a guild role is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildRoleCreateEventArgs> GuildRoleCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildRoleCreateEventArgs](DSharpPlus.EventArgs.GuildRoleCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildRoleDeleted"></a>GuildRoleDeleted

Fired when a guild role is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildRoleDeleteEventArgs> GuildRoleDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildRoleDeleteEventArgs](DSharpPlus.EventArgs.GuildRoleDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildRoleUpdated"></a>GuildRoleUpdated

Fired when a guild role is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildRoleUpdateEventArgs> GuildRoleUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildRoleUpdateEventArgs](DSharpPlus.EventArgs.GuildRoleUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildStickersUpdated"></a>GuildStickersUpdated

```csharp
public event AsyncEventHandler<DiscordClient, GuildStickersUpdateEventArgs> GuildStickersUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildStickersUpdateEventArgs](DSharpPlus.EventArgs.GuildStickersUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildUnavailable"></a>GuildUnavailable

Fired when a guild becomes unavailable.

```csharp
public event AsyncEventHandler<DiscordClient, GuildDeleteEventArgs> GuildUnavailable
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildDeleteEventArgs](DSharpPlus.EventArgs.GuildDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_GuildUpdated"></a>GuildUpdated

Fired when a guild is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildUpdateEventArgs> GuildUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildUpdateEventArgs](DSharpPlus.EventArgs.GuildUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_Heartbeated"></a>Heartbeated

Fired on received heartbeat ACK.

```csharp
public event AsyncEventHandler<DiscordClient, HeartbeatEventArgs> Heartbeated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [HeartbeatEventArgs](DSharpPlus.EventArgs.HeartbeatEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_IntegrationCreated"></a>IntegrationCreated

Fired when an integration is created.

```csharp
public event AsyncEventHandler<DiscordClient, IntegrationCreateEventArgs> IntegrationCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [IntegrationCreateEventArgs](DSharpPlus.EventArgs.IntegrationCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_IntegrationDeleted"></a>IntegrationDeleted

Fired when an integration is deleted.

```csharp
public event AsyncEventHandler<DiscordClient, IntegrationDeleteEventArgs> IntegrationDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [IntegrationDeleteEventArgs](DSharpPlus.EventArgs.IntegrationDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_IntegrationUpdated"></a>IntegrationUpdated

Fired when an integration is updated.

```csharp
public event AsyncEventHandler<DiscordClient, IntegrationUpdateEventArgs> IntegrationUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [IntegrationUpdateEventArgs](DSharpPlus.EventArgs.IntegrationUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_InteractionCreated"></a>InteractionCreated

Fired when an interaction is invoked.

```csharp
public event AsyncEventHandler<DiscordClient, InteractionCreateEventArgs> InteractionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [InteractionCreateEventArgs](DSharpPlus.EventArgs.InteractionCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_InviteCreated"></a>InviteCreated

Fired when an invite is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildInvites" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, InviteCreateEventArgs> InviteCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [InviteCreateEventArgs](DSharpPlus.EventArgs.InviteCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_InviteDeleted"></a>InviteDeleted

Fired when an invite is deleted.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildInvites" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, InviteDeleteEventArgs> InviteDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [InviteDeleteEventArgs](DSharpPlus.EventArgs.InviteDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageAcknowledged"></a>MessageAcknowledged

Fired when message is acknowledged by the user.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageAcknowledgeEventArgs> MessageAcknowledged
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageAcknowledgeEventArgs](DSharpPlus.EventArgs.MessageAcknowledgeEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageCreated"></a>MessageCreated

Fired when a message is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageCreateEventArgs> MessageCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageCreateEventArgs](DSharpPlus.EventArgs.MessageCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageDeleted"></a>MessageDeleted

Fired when a message is deleted.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageDeleteEventArgs> MessageDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageDeleteEventArgs](DSharpPlus.EventArgs.MessageDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageReactionAdded"></a>MessageReactionAdded

Fired when a reaction gets added to a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionAddEventArgs> MessageReactionAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageReactionRemoved"></a>MessageReactionRemoved

Fired when a reaction gets removed from a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionRemoveEventArgs> MessageReactionRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionRemoveEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageReactionRemovedEmoji"></a>MessageReactionRemovedEmoji

Fired when all reactions of a specific reaction are removed from a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionRemoveEmojiEventArgs> MessageReactionRemovedEmoji
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionRemoveEmojiEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEmojiEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageReactionsCleared"></a>MessageReactionsCleared

Fired when all reactions get removed from a message.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessageReactions" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageReactionsClearEventArgs> MessageReactionsCleared
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageReactionsClearEventArgs](DSharpPlus.EventArgs.MessageReactionsClearEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessageUpdated"></a>MessageUpdated

Fired when a message is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageUpdateEventArgs> MessageUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageUpdateEventArgs](DSharpPlus.EventArgs.MessageUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_MessagesBulkDeleted"></a>MessagesBulkDeleted

Fired when multiple messages are deleted at once.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMessages" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, MessageBulkDeleteEventArgs> MessagesBulkDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [MessageBulkDeleteEventArgs](DSharpPlus.EventArgs.MessageBulkDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ModalSubmitted"></a>ModalSubmitted

Fired when a modal is submitted. If a modal is closed, this event is not fired.

```csharp
public event AsyncEventHandler<DiscordClient, ModalSubmitEventArgs> ModalSubmitted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ModalSubmitEventArgs](DSharpPlus.EventArgs.ModalSubmitEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_PresenceUpdated"></a>PresenceUpdated

Fired when a presence has been updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, PresenceUpdateEventArgs> PresenceUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [PresenceUpdateEventArgs](DSharpPlus.EventArgs.PresenceUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ScheduledGuildEventCompleted"></a>ScheduledGuildEventCompleted

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventCompletedEventArgs> ScheduledGuildEventCompleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventCompletedEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventCompletedEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ScheduledGuildEventCreated"></a>ScheduledGuildEventCreated

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventCreateEventArgs> ScheduledGuildEventCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventCreateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ScheduledGuildEventDeleted"></a>ScheduledGuildEventDeleted

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventDeleteEventArgs> ScheduledGuildEventDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventDeleteEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ScheduledGuildEventUpdated"></a>ScheduledGuildEventUpdated

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventUpdateEventArgs> ScheduledGuildEventUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventUpdateEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ScheduledGuildEventUserAdded"></a>ScheduledGuildEventUserAdded

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventUserAddEventArgs> ScheduledGuildEventUserAdded
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventUserAddEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserAddEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ScheduledGuildEventUserRemoved"></a>ScheduledGuildEventUserRemoved

```csharp
public event AsyncEventHandler<DiscordClient, ScheduledGuildEventUserRemoveEventArgs> ScheduledGuildEventUserRemoved
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ScheduledGuildEventUserRemoveEventArgs](DSharpPlus.EventArgs.ScheduledGuildEventUserRemoveEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_SessionCreated"></a>SessionCreated

Fired when this client has successfully completed its handshake with the websocket gateway.

```csharp
public event AsyncEventHandler<DiscordClient, SessionReadyEventArgs> SessionCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SessionReadyEventArgs](DSharpPlus.EventArgs.SessionReadyEventArgs.md)\>

#### Remarks

<i><xref href="DSharpPlus.DiscordClient.Guilds" data-throw-if-not-resolved="false"></xref> will not be populated when this event is fired.</i><br />
See also: <xref href="DSharpPlus.DiscordClient.GuildAvailable" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildDownloadCompleted" data-throw-if-not-resolved="false"></xref>

### <a id="DSharpPlus_DiscordClient_SessionResumed"></a>SessionResumed

Fired whenever a session is resumed.

```csharp
public event AsyncEventHandler<DiscordClient, SessionReadyEventArgs> SessionResumed
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SessionReadyEventArgs](DSharpPlus.EventArgs.SessionReadyEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_SocketClosed"></a>SocketClosed

Fired whenever WebSocket connection is terminated.

```csharp
public event AsyncEventHandler<DiscordClient, SocketCloseEventArgs> SocketClosed
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SocketCloseEventArgs](DSharpPlus.EventArgs.SocketCloseEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_SocketErrored"></a>SocketErrored

Fired whenever a WebSocket error occurs within the client.

```csharp
public event AsyncEventHandler<DiscordClient, SocketErrorEventArgs> SocketErrored
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SocketErrorEventArgs](DSharpPlus.EventArgs.SocketErrorEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_SocketOpened"></a>SocketOpened

Fired whenever WebSocket connection is established.

```csharp
public event AsyncEventHandler<DiscordClient, SocketEventArgs> SocketOpened
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SocketEventArgs](DSharpPlus.EventArgs.SocketEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_StageInstanceCreated"></a>StageInstanceCreated

Fired when a stage instance is created.

```csharp
public event AsyncEventHandler<DiscordClient, StageInstanceCreateEventArgs> StageInstanceCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [StageInstanceCreateEventArgs](DSharpPlus.EventArgs.StageInstanceCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_StageInstanceDeleted"></a>StageInstanceDeleted

Fired when a stage instance is deleted.

```csharp
public event AsyncEventHandler<DiscordClient, StageInstanceDeleteEventArgs> StageInstanceDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [StageInstanceDeleteEventArgs](DSharpPlus.EventArgs.StageInstanceDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_StageInstanceUpdated"></a>StageInstanceUpdated

Fired when a stage instance is updated.

```csharp
public event AsyncEventHandler<DiscordClient, StageInstanceUpdateEventArgs> StageInstanceUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [StageInstanceUpdateEventArgs](DSharpPlus.EventArgs.StageInstanceUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ThreadCreated"></a>ThreadCreated

Fired when a thread is created.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadCreateEventArgs> ThreadCreated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadCreateEventArgs](DSharpPlus.EventArgs.ThreadCreateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ThreadDeleted"></a>ThreadDeleted

Fired when a thread is deleted.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadDeleteEventArgs> ThreadDeleted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadDeleteEventArgs](DSharpPlus.EventArgs.ThreadDeleteEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ThreadListSynced"></a>ThreadListSynced

Fired when the current member gains access to a channel(s) that has threads.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadListSyncEventArgs> ThreadListSynced
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadListSyncEventArgs](DSharpPlus.EventArgs.ThreadListSyncEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ThreadMemberUpdated"></a>ThreadMemberUpdated

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

### <a id="DSharpPlus_DiscordClient_ThreadMembersUpdated"></a>ThreadMembersUpdated

Fired when the thread members are updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadMembersUpdateEventArgs> ThreadMembersUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadMembersUpdateEventArgs](DSharpPlus.EventArgs.ThreadMembersUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_ThreadUpdated"></a>ThreadUpdated

Fired when a thread is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadUpdateEventArgs> ThreadUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadUpdateEventArgs](DSharpPlus.EventArgs.ThreadUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_TypingStarted"></a>TypingStarted

Fired when a user starts typing in a channel.

```csharp
public event AsyncEventHandler<DiscordClient, TypingStartEventArgs> TypingStarted
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [TypingStartEventArgs](DSharpPlus.EventArgs.TypingStartEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_UnknownEvent"></a>UnknownEvent

Fired when an unknown event gets received.

```csharp
public event AsyncEventHandler<DiscordClient, UnknownEventArgs> UnknownEvent
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [UnknownEventArgs](DSharpPlus.EventArgs.UnknownEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_UserSettingsUpdated"></a>UserSettingsUpdated

Fired when the current user updates their settings.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, UserSettingsUpdateEventArgs> UserSettingsUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [UserSettingsUpdateEventArgs](DSharpPlus.EventArgs.UserSettingsUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_UserUpdated"></a>UserUpdated

Fired when properties about the current user change.

```csharp
public event AsyncEventHandler<DiscordClient, UserUpdateEventArgs> UserUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [UserUpdateEventArgs](DSharpPlus.EventArgs.UserUpdateEventArgs.md)\>

#### Remarks

NB: This event only applies for changes to the <b>current user</b>, the client that is connected to Discord.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

### <a id="DSharpPlus_DiscordClient_VoiceServerUpdated"></a>VoiceServerUpdated

Fired when a guild's voice server is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildVoiceStates" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, VoiceServerUpdateEventArgs> VoiceServerUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [VoiceServerUpdateEventArgs](DSharpPlus.EventArgs.VoiceServerUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_VoiceStateUpdated"></a>VoiceStateUpdated

Fired when someone joins/leaves/moves voice channels.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildVoiceStates" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, VoiceStateUpdateEventArgs> VoiceStateUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [VoiceStateUpdateEventArgs](DSharpPlus.EventArgs.VoiceStateUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_WebhooksUpdated"></a>WebhooksUpdated

Fired whenever webhooks update.

```csharp
public event AsyncEventHandler<DiscordClient, WebhooksUpdateEventArgs> WebhooksUpdated
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [WebhooksUpdateEventArgs](DSharpPlus.EventArgs.WebhooksUpdateEventArgs.md)\>

### <a id="DSharpPlus_DiscordClient_Zombied"></a>Zombied

Fired on heartbeat attempt cancellation due to too many failed heartbeats.

```csharp
public event AsyncEventHandler<DiscordClient, ZombiedEventArgs> Zombied
```

#### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ZombiedEventArgs](DSharpPlus.EventArgs.ZombiedEventArgs.md)\>

