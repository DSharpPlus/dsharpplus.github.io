# Class DiscordFollowedChannel

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a followed channel.

```csharp
public class DiscordFollowedChannel
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordFollowedChannel](DSharpPlus.Entities.DiscordFollowedChannel.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordFollowedChannel_ChannelId"></a>ChannelId

Gets the ID of the channel following the announcement channel.

```csharp
[JsonProperty("channel_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordFollowedChannel_WebhookId"></a>WebhookId

Gets the ID of the webhook that posts crossposted messages to the channel.

```csharp
[JsonProperty("webhook_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong WebhookId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

