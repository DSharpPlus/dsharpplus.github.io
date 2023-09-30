# Method GetIdealNodeConnection

Namespace: [DSharpPlus.Lavalink](DSharpPlus.Lavalink.md)  
Assembly: DSharpPlus.Lavalink.dll

## <a id="DSharpPlus_Lavalink_LavalinkExtension_GetIdealNodeConnection_DSharpPlus_Entities_DiscordVoiceRegion_"></a>GetIdealNodeConnection\(DiscordVoiceRegion\)

Gets a Lavalink node connection based on load balancing and an optional voice region.

```csharp
public LavalinkNodeConnection GetIdealNodeConnection(DiscordVoiceRegion region = null)
```

### Parameters

`region` [DiscordVoiceRegion](DSharpPlus.Entities.DiscordVoiceRegion.md)

The region to compare with the node's <xref href="DSharpPlus.Lavalink.LavalinkConfiguration.Region" data-throw-if-not-resolved="false"></xref>, if any.

### Returns

[LavalinkNodeConnection](DSharpPlus.Lavalink.LavalinkNodeConnection.md)

The least load affected node connection, or null if no nodes are present.

