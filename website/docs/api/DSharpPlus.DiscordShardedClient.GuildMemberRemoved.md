# Event GuildMemberRemoved

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordShardedClient_GuildMemberRemoved"></a>GuildMemberRemoved

Fired when a user is removed from a guild (leave/kick/ban).
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public event AsyncEventHandler<DiscordClient, GuildMemberRemoveEventArgs> GuildMemberRemoved
```

### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [GuildMemberRemoveEventArgs](DSharpPlus.EventArgs.GuildMemberRemoveEventArgs.md)\>

