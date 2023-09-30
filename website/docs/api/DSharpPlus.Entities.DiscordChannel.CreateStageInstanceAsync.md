# Method CreateStageInstanceAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_CreateStageInstanceAsync_System_String_System_Nullable_DSharpPlus_PrivacyLevel__System_String_"></a>CreateStageInstanceAsync\(string, PrivacyLevel?, string\)

Creates a stage instance in this stage channel.

```csharp
public Task<DiscordStageInstance> CreateStageInstanceAsync(string topic, PrivacyLevel? privacyLevel = null, string reason = null)
```

### Parameters

`topic` [string](https://learn.microsoft.com/dotnet/api/system.string)

The topic of the stage instance.

`privacyLevel` [PrivacyLevel](DSharpPlus.PrivacyLevel.md)?

The privacy level of the stage instance.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason the stage instance was created.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The created stage instance.

