# Method CreateGuildAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_CreateGuildAsync_System_String_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__System_Nullable_DSharpPlus_Entities_VerificationLevel__System_Nullable_DSharpPlus_Entities_DefaultMessageNotifications__System_Nullable_DSharpPlus_SystemChannelFlags__"></a>CreateGuildAsync\(string, string, Optional<Stream\>, VerificationLevel?, DefaultMessageNotifications?, SystemChannelFlags?\)

Creates a guild. This requires the bot to be in less than 10 guilds total.

```csharp
public Task<DiscordGuild> CreateGuildAsync(string name, string region = null, Optional<Stream> icon = default, VerificationLevel? verificationLevel = null, DefaultMessageNotifications? defaultMessageNotifications = null, SystemChannelFlags? systemChannelFlags = null)
```

### Parameters

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

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

The created guild.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

