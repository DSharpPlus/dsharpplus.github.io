# Property PublicUpdatesChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_PublicUpdatesChannel"></a>PublicUpdatesChannel

Gets the public updates channel (where admins and moderators receive messages from Discord) for this guild.
<p>This is only available if the guild is considered "discoverable".</p>

```csharp
[JsonIgnore]
public DiscordChannel PublicUpdatesChannel { get; }
```

### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

