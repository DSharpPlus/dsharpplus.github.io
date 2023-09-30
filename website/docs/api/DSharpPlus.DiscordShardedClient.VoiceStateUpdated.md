# Event VoiceStateUpdated

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordShardedClient_VoiceStateUpdated"></a>VoiceStateUpdated

Fired when someone joins/leaves/moves voice channels.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildVoiceStates" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, VoiceStateUpdateEventArgs> VoiceStateUpdated
```

### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [VoiceStateUpdateEventArgs](DSharpPlus.EventArgs.VoiceStateUpdateEventArgs.md)\>

