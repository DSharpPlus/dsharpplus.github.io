# Method UpdateVoiceStateAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMember_UpdateVoiceStateAsync_DSharpPlus_Entities_DiscordChannel_System_Nullable_System_Boolean__"></a>UpdateVoiceStateAsync\(DiscordChannel, bool?\)

Updates the member's suppress state in a stage channel.

```csharp
public Task UpdateVoiceStateAsync(DiscordChannel channel, bool? suppress)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

The channel the member is currently in.

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the member's suppress state.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the channel in not a voice channel.

