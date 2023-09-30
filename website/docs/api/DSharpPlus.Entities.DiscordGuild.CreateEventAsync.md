# Method CreateEventAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateEventAsync_System_String_System_String_System_Nullable_System_UInt64__DSharpPlus_Entities_ScheduledGuildEventType_DSharpPlus_Entities_ScheduledGuildEventPrivacyLevel_System_DateTimeOffset_System_Nullable_System_DateTimeOffset__System_String_System_String_"></a>CreateEventAsync\(string, string, ulong?, ScheduledGuildEventType, ScheduledGuildEventPrivacyLevel, DateTimeOffset, DateTimeOffset?, string, string\)

Creates a new scheduled event in this guild.

```csharp
public Task<DiscordScheduledGuildEvent> CreateEventAsync(string name, string description, ulong? channelId, ScheduledGuildEventType type, ScheduledGuildEventPrivacyLevel privacyLevel, DateTimeOffset start, DateTimeOffset? end, string location = null, string reason = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the event to create, up to 100 characters.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the event, up to 1000 characters.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

If a <xref href="DSharpPlus.Entities.ScheduledGuildEventType.StageInstance" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.Entities.ScheduledGuildEventType.VoiceChannel" data-throw-if-not-resolved="false"></xref>, the id of the channel the event will be hosted in

`type` [ScheduledGuildEventType](DSharpPlus.Entities.ScheduledGuildEventType.md)

The type of the event. <see paramref="channelId"></see> must be supplied if not an external event.

`privacyLevel` [ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)

The privacy level of thi

`start` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

When this event starts. Must be in the future, and before the end date.

`end` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

When this event ends. If supplied, must be in the future and after the end date. This is required for <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>.

`location` [string](https://learn.microsoft.com/dotnet/api/system.string)

Where this event takes place, up to 100 characters. Only applicable if the type is <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The created event.

