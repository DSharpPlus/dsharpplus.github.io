# Method ModifyStageInstanceAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyStageInstanceAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_StageInstanceEditModel__"></a>ModifyStageInstanceAsync\(ulong, Action<StageInstanceEditModel\>\)

Modifies a stage instance in a stage channel.

```csharp
public Task<DiscordStageInstance> ModifyStageInstanceAsync(ulong channelId, Action<StageInstanceEditModel> action)
```

### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel to modify the stage instance of.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StageInstanceEditModel](DSharpPlus.Net.Models.StageInstanceEditModel.md)\>

Action to perform.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The modified stage instance.

