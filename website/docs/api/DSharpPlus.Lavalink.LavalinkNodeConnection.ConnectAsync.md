# Method ConnectAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkNodeConnection_ConnectAsync_DSharpPlus_Entities_DiscordChannel_"></a>ConnectAsync\(DiscordChannel\)

Connects this Lavalink node to specified Discord channel.

```csharp
public Task<LavalinkGuildConnection> ConnectAsync(DiscordChannel channel)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Voice channel to connect to.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)\>

Channel connection, which allows for playback control.

