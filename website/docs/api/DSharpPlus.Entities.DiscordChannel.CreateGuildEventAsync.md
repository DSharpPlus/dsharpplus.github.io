# Method CreateGuildEventAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_CreateGuildEventAsync_System_String_System_String_DSharpPlus_Entities_ScheduledGuildEventPrivacyLevel_System_DateTimeOffset_System_Nullable_System_DateTimeOffset__"></a>CreateGuildEventAsync\(string, string, ScheduledGuildEventPrivacyLevel, DateTimeOffset, DateTimeOffset?\)

Creates an event bound to this channel.

```csharp
public Task<DiscordScheduledGuildEvent> CreateGuildEventAsync(string name, string description, ScheduledGuildEventPrivacyLevel privacyLevel, DateTimeOffset start, DateTimeOffset? end)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the event, up to 100 characters.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

The description of this event, up to 1000 characters.

`privacyLevel` [ScheduledGuildEventPrivacyLevel](DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.md)

The privacy level. Currently only <xref href="DSharpPlus.Entities.ScheduledGuildEventPrivacyLevel.GuildOnly" data-throw-if-not-resolved="false"></xref> is supported

`start` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)

When this event starts.

`end` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

When this event ends. External events require an end time.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)\>

The created event.

### Exceptions

[InvalidOperationException](https://learn.microsoft.com/dotnet/api/system.invalidoperationexception)

