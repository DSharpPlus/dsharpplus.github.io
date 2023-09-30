# Method ModifyGuildAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildAsync_System_UInt64_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_DSharpPlus_Entities_VerificationLevel__DSharpPlus_Entities_Optional_DSharpPlus_Entities_DefaultMessageNotifications__DSharpPlus_Entities_Optional_DSharpPlus_Entities_MfaLevel__DSharpPlus_Entities_Optional_DSharpPlus_Entities_ExplicitContentFilter__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_Int32__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_UInt64__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Collections_Generic_IEnumerable_System_String___DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_DSharpPlus_SystemChannelFlags__System_String_"></a>ModifyGuildAsync\(ulong, Optional<string\>, Optional<string\>, Optional<VerificationLevel\>, Optional<DefaultMessageNotifications\>, Optional<MfaLevel\>, Optional<ExplicitContentFilter\>, Optional<ulong?\>, Optional<int\>, Optional<string\>, Optional<ulong\>, Optional<string\>, Optional<ulong?\>, Optional<string\>, Optional<string\>, Optional<string\>, Optional<IEnumerable<string\>\>, Optional<string\>, Optional<ulong?\>, Optional<ulong?\>, Optional<SystemChannelFlags\>, string\)

Modifies a guild

```csharp
public Task<DiscordGuild> ModifyGuildAsync(ulong guild_id, Optional<string> name, Optional<string> region, Optional<VerificationLevel> verification_level, Optional<DefaultMessageNotifications> default_message_notifications, Optional<MfaLevel> mfa_level, Optional<ExplicitContentFilter> explicit_content_filter, Optional<ulong?> afk_channel_id, Optional<int> afk_timeout, Optional<string> iconb64, Optional<ulong> owner_id, Optional<string> splashb64, Optional<ulong?> systemChannelId, Optional<string> banner, Optional<string> description, Optional<string> discorverySplash, Optional<IEnumerable<string>> features, Optional<string> preferredLocale, Optional<ulong?> publicUpdatesChannelId, Optional<ulong?> rulesChannelId, Optional<SystemChannelFlags> systemChannelFlags, string reason)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`name` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild Name

`region` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild voice region

`verification\_level` [Optional](DSharpPlus.Entities.Optional\-1.md)<[VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)\>

New guild verification level

`default\_message\_notifications` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)\>

New guild default message notification level

`mfa\_level` [Optional](DSharpPlus.Entities.Optional\-1.md)<[MfaLevel](DSharpPlus.Entities.MfaLevel.md)\>

New guild MFA level

`explicit\_content\_filter` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ExplicitContentFilter](DSharpPlus.Entities.ExplicitContentFilter.md)\>

New guild explicit content filter level

`afk\_channel\_id` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New guild AFK channel ID

`afk\_timeout` [Optional](DSharpPlus.Entities.Optional\-1.md)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

New guild AFK timeout in seconds

`iconb64` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild icon (base64)

`owner\_id` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

New guild owner ID

`splashb64` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild splash (base64)

`systemChannelId` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New guild system channel ID

`banner` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild banner

`description` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild description

`discorverySplash` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New guild Discovery splash

`features` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>\>

List of new <a href="https://discord.com/developers/docs/resources/guild#guild-object-guild-features">guild features</a>

`preferredLocale` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New preferred locale

`publicUpdatesChannelId` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New updates channel ID

`rulesChannelId` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

New rules channel ID

`systemChannelFlags` [Optional](DSharpPlus.Entities.Optional\-1.md)<[SystemChannelFlags](DSharpPlus.SystemChannelFlags.md)\>

New system channel flags

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Modify reason

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_GuildEditModel__"></a>ModifyGuildAsync\(ulong, Action<GuildEditModel\>\)

Modifies a guild

```csharp
public Task<DiscordGuild> ModifyGuildAsync(ulong guild_id, Action<GuildEditModel> action)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[GuildEditModel](DSharpPlus.Net.Models.GuildEditModel.md)\>

Guild modifications

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

