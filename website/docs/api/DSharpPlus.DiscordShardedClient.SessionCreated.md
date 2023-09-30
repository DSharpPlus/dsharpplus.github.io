# Event SessionCreated

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordShardedClient_SessionCreated"></a>SessionCreated

Fired when this client has successfully completed its handshake with the websocket gateway.

```csharp
public event AsyncEventHandler<DiscordClient, SessionReadyEventArgs> SessionCreated
```

### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [SessionReadyEventArgs](DSharpPlus.EventArgs.SessionReadyEventArgs.md)\>

### Remarks

<i>
  <xref href="DSharpPlus.DiscordClient.Guilds" data-throw-if-not-resolved="false"></xref> will not be populated when this event is fired.</i>
<br />
    See also: <xref href="DSharpPlus.DiscordClient.GuildAvailable" data-throw-if-not-resolved="false"></xref>, <xref href="DSharpPlus.DiscordClient.GuildDownloadCompleted" data-throw-if-not-resolved="false"></xref>

