# Class DiscordGuildEmbed

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord guild widget.

```csharp
public class DiscordGuildEmbed
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordGuildEmbed](DSharpPlus.Entities.DiscordGuildEmbed.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordGuildEmbed_ChannelId"></a>ChannelId

Gets the ID of the widget channel.

```csharp
[JsonProperty("channel_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ChannelId { get; set; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordGuildEmbed_IsEnabled"></a>IsEnabled

Gets whether the embed is enabled.

```csharp
[JsonProperty("enabled", NullValueHandling = NullValueHandling.Ignore)]
public bool IsEnabled { get; set; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

