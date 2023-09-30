# Method GetGuildConnection

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkExtension_GetGuildConnection_DSharpPlus_Entities_DiscordGuild_"></a>GetGuildConnection\(DiscordGuild\)

Gets a Lavalink guild connection from a <xref href="DSharpPlus.Entities.DiscordGuild" data-throw-if-not-resolved="false"></xref>.

```csharp
public LavalinkGuildConnection GetGuildConnection(DiscordGuild guild)
```

### Parameters

`guild` [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

The guild the connection is on.

### Returns

[LavalinkGuildConnection](DSharpPlus.Lavalink.LavalinkGuildConnection.md)

The found guild connection, or null if one could not be found.

