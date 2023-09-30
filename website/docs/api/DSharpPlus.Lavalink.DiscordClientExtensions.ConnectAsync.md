# Method ConnectAsync

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_DiscordClientExtensions_ConnectAsync_DSharpPlus_Entities_DiscordChannel_DSharpPlus_Lavalink_LavalinkNodeConnection_"></a>ConnectAsync\(DiscordChannel, LavalinkNodeConnection\)

Connects to this voice channel using Lavalink.

```csharp
public static Task ConnectAsync(this DiscordChannel channel, LavalinkNodeConnection node)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to connect to.

`node` [LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

Lavalink node to connect through.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

If successful, the Lavalink client.

