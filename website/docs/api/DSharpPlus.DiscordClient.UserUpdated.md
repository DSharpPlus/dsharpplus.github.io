# Event UserUpdated

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_UserUpdated"></a>UserUpdated

Fired when properties about the current user change.

```csharp
public event AsyncEventHandler<DiscordClient, UserUpdateEventArgs> UserUpdated
```

### Event Type

[AsyncEventHandler](DSharpPlus.AsyncEvents.AsyncEventHandler\-2.md)<[DiscordClient](DSharpPlus.DiscordClient.md), [UserUpdateEventArgs](DSharpPlus.EventArgs.UserUpdateEventArgs.md)\>

### Remarks

NB: This event only applies for changes to the <b>current user</b>, the client that is connected to Discord.
For this Event you need the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

