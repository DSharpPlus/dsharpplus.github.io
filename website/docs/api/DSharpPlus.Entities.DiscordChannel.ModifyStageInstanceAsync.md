# Method ModifyStageInstanceAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_ModifyStageInstanceAsync_System_Action_DSharpPlus_Net_Models_StageInstanceEditModel__"></a>ModifyStageInstanceAsync\(Action<StageInstanceEditModel\>\)

Modifies the stage instance in this stage channel.

```csharp
public Task<DiscordStageInstance> ModifyStageInstanceAsync(Action<StageInstanceEditModel> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[StageInstanceEditModel](DSharpPlus.Net.Models.StageInstanceEditModel.md)\>

Action to perform.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordStageInstance](DSharpPlus.Entities.DiscordStageInstance.md)\>

The modified stage instance.

