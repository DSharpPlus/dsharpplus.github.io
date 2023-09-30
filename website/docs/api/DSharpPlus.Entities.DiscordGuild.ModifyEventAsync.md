# Method ModifyEventAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyEventAsync_DSharpPlus_Entities_DiscordScheduledGuildEvent_System_Action_DSharpPlus_Net_Models_ScheduledGuildEventEditModel__System_String_"></a>ModifyEventAsync\(DiscordScheduledGuildEvent, Action<ScheduledGuildEventEditModel\>, string\)

Modifies an existing scheduled event in this guild.

```csharp
public Task ModifyEventAsync(DiscordScheduledGuildEvent guildEvent, Action<ScheduledGuildEventEditModel> mdl, string reason = null)
```

### Parameters

`guildEvent` [DiscordScheduledGuildEvent](DSharpPlus.Entities.DiscordScheduledGuildEvent.md)

The event to modify.

`mdl` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[ScheduledGuildEventEditModel](DSharpPlus.Net.Models.ScheduledGuildEventEditModel.md)\>

The action to perform on this event

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The reason this event is being modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

The modified object

### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

