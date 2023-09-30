# Method GetStageInstanceAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetStageInstanceAsync_System_UInt64_"></a>GetStageInstanceAsync\(ulong\)

Gets a stage instance in a stage channel.

```csharp
public Task<DiscordStageInstance> GetStageInstanceAsync(ulong channelId)
```

### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The stage instance in the channel.

