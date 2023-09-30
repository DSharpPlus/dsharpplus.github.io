# Method CreateGuildAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildAsync_System_String_System_String_System_String_System_Nullable_DSharpPlus_Entities_VerificationLevel__System_Nullable_DSharpPlus_Entities_DefaultMessageNotifications__System_Nullable_DSharpPlus_SystemChannelFlags__"></a>CreateGuildAsync\(string, string, string, VerificationLevel?, DefaultMessageNotifications?, SystemChannelFlags?\)

Creates a new guild

```csharp
public Task<DiscordGuild> CreateGuildAsync(string name, string region_id, string iconb64, VerificationLevel? verification_level, DefaultMessageNotifications? default_message_notifications, SystemChannelFlags? system_channel_flags)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

New guild's name

`region\_id` [string](https://learn.microsoft.com/dotnet/api/system.string)

New guild's region ID

`iconb64` [string](https://learn.microsoft.com/dotnet/api/system.string)

New guild's icon (base64)

`verification\_level` [VerificationLevel](DSharpPlus.Entities.VerificationLevel.md)?

New guild's verification level

`default\_message\_notifications` [DefaultMessageNotifications](DSharpPlus.Entities.DefaultMessageNotifications.md)?

New guild's default message notification level

`system\_channel\_flags` [SystemChannelFlags](DSharpPlus.SystemChannelFlags.md)?

New guild's system channel flags

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

