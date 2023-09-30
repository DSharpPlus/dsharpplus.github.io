# Class DiscordWidgetSettings

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord guild's widget settings.

```csharp
public class DiscordWidgetSettings
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordWidgetSettings](DSharpPlus.Entities.DiscordWidgetSettings.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordWidgetSettings_Channel"></a>Channel

Gets the guild's widget channel.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_Entities_DiscordWidgetSettings_ChannelId"></a>ChannelId

Gets the guild's widget channel id.

```csharp
[JsonProperty("channel_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordWidgetSettings_IsEnabled"></a>IsEnabled

Gets if the guild's widget is enabled.

```csharp
[JsonProperty("enabled", NullValueHandling = NullValueHandling.Ignore)]
public bool IsEnabled { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

