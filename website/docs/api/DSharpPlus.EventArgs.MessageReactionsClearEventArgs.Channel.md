# Property Channel

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_EventArgs_MessageReactionsClearEventArgs_Channel"></a>Channel

Gets the channel to which this message belongs.

```csharp
public DiscordChannel Channel { get; }
```

### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### Remarks

This will be <code>null</code> for an uncached channel, which will usually happen for when this event triggers on
DM channels in which no prior messages were received or sent.

