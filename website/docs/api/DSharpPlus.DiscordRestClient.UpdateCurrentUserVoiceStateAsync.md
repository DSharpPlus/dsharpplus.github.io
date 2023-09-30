# Method UpdateCurrentUserVoiceStateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_UpdateCurrentUserVoiceStateAsync_System_UInt64_System_UInt64_System_Nullable_System_Boolean__System_Nullable_System_DateTimeOffset__"></a>UpdateCurrentUserVoiceStateAsync\(ulong, ulong, bool?, DateTimeOffset?\)

Updates the current user's suppress state in a stage channel.

```csharp
public Task UpdateCurrentUserVoiceStateAsync(ulong guildId, ulong channelId, bool? suppress, DateTimeOffset? requestToSpeakTimestamp = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the suppress state.

`requestToSpeakTimestamp` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Sets the time the user requested to speak.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

