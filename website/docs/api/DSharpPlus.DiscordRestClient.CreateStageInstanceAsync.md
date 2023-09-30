# Method CreateStageInstanceAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateStageInstanceAsync_System_UInt64_System_String_System_Nullable_DSharpPlus_PrivacyLevel__System_String_"></a>CreateStageInstanceAsync\(ulong, string, PrivacyLevel?, string\)

Creates a stage instance in a stage channel.

```csharp
public Task<DiscordStageInstance> CreateStageInstanceAsync(ulong channelId, string topic, PrivacyLevel? privacyLevel = null, string reason = null)
```

### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the stage channel to create it in.

`topic` [string](https://learn.microsoft.com/dotnet/api/system.string)

The topic of the stage instance.

`privacyLevel` [PrivacyLevel](DSharpPlus.PrivacyLevel.md)?

The privacy level of the stage instance.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason the stage instance was created.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The created stage instance.

