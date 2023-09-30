# Event ThreadListSynced

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordShardedClient_ThreadListSynced"></a>ThreadListSynced

Fired when the current member gains access to a channel(s) that has threads.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadListSyncEventArgs> ThreadListSynced
```

### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadListSyncEventArgs](DSharpPlus.EventArgs.ThreadListSyncEventArgs.md)\>

