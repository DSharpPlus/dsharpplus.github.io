# Event ThreadMemberUpdated

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordShardedClient_ThreadMemberUpdated"></a>ThreadMemberUpdated

Fired when the thread member for the current user is updated.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.Guilds" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, ThreadMemberUpdateEventArgs> ThreadMemberUpdated
```

### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [ThreadMemberUpdateEventArgs](DSharpPlus.EventArgs.ThreadMemberUpdateEventArgs.md)\>

### Remarks

This event is mostly documented for completeness, and it not fired every time
DM channels in which no prior messages were received or sent.

