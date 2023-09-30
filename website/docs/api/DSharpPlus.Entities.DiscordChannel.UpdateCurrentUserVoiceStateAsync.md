# Method UpdateCurrentUserVoiceStateAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_UpdateCurrentUserVoiceStateAsync_System_Nullable_System_Boolean__System_Nullable_System_DateTimeOffset__"></a>UpdateCurrentUserVoiceStateAsync\(bool?, DateTimeOffset?\)

Updates the current user's suppress state in this channel, if stage channel.

```csharp
public Task UpdateCurrentUserVoiceStateAsync(bool? suppress, DateTimeOffset? requestToSpeakTimestamp = null)
```

### Parameters

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the suppress state.

`requestToSpeakTimestamp` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

Sets the time the user requested to speak.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the channel is not a stage channel.

