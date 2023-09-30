# Method CreateScheduledGuildEventAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateScheduledGuildEventAsync_System_UInt64_System_String_System_String_System_Nullable_System_UInt64__DSharpPlus_Entities_ScheduledGuildEventType_DSharpPlus_Entities_ScheduledGuildEventPrivacyLevel_System_DateTimeOffset_System_Nullable_System_DateTimeOffset__System_String_"></a>CreateScheduledGuildEventAsync\(ulong, string, string, ulong?, ScheduledGuildEventType, ScheduledGuildEventPrivacyLevel, DateTimeOffset, DateTimeOffset?, string\)

Creates a new scheduled guild event.

```csharp
public Task<DiscordScheduledGuildEvent> CreateScheduledGuildEventAsync(ulong guildId, string name, string description, ulong? channelId, ScheduledGuildEventType type, ScheduledGuildEventPrivacyLevel privacyLevel, DateTimeOffset start, DateTimeOffset? end, string location = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild to create an event on.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the event, up to 100 characters.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of the event, up to 1000 characters.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The channel the event will take place in, if applicable.

`type` [ScheduledGuildEventType](DSharpPlus.Entities.ScheduledGuildEventType.md)

The type of event. If <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>, a end time must be specified.

`privacyLevel` [ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)

The privacy level of the event.

`start` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

When the event starts. Must be in the future and before the end date, if specified.

`end` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

When the event ends. Required for <xref href="DSharpPlus.Entities.ScheduledGuildEventType.External" data-throw-if-not-resolved="false"></xref>

`location` [string](https://learn.microsoft.com/dotnet/api/system.string)

Where this location takes place.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The created event.

