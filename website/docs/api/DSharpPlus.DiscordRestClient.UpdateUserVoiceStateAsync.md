# Method UpdateUserVoiceStateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_UpdateUserVoiceStateAsync_System_UInt64_System_UInt64_System_UInt64_System_Nullable_System_Boolean__"></a>UpdateUserVoiceStateAsync\(ulong, ulong, ulong, bool?\)

Updates a member's suppress state in a stage channel.

```csharp
public Task UpdateUserVoiceStateAsync(ulong guildId, ulong userId, ulong channelId, bool? suppress)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the member.

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the stage channel.

`suppress` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Toggles the member's suppress state.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

