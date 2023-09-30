# Method ConnectAsync

Namespace: [DSharpPlus.VoiceNext](DSharpPlus.VoiceNext.md)  
Assembly: DSharpPlus.VoiceNext.dll

## <a id="DSharpPlus_VoiceNext_DiscordClientExtensions_ConnectAsync_DSharpPlus_Entities_DiscordChannel_"></a>ConnectAsync\(DiscordChannel\)

Connects to this voice channel using VoiceNext.

```csharp
public static Task<VoiceNextConnection> ConnectAsync(this DiscordChannel channel)
```

### Parameters

`channel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to connect to.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[VoiceNextConnection](DSharpPlus.VoiceNext.VoiceNextConnection.md)\>

If successful, the VoiceNext connection.

