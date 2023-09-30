# Class DiscordRuleActionMetadata

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

Represents a Discord rule action metadata.

```csharp
public class DiscordRuleActionMetadata
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordRuleActionMetadata](DSharpPlus.Entities.DiscordRuleActionMetadata.md)

## Properties

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadata_ChannelId"></a>ChannelId

Gets the channel which the blocked content should be logged.

```csharp
[JsonProperty("channel_id")]
public ulong ChannelId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadata_CustomMessage"></a>CustomMessage

Gets the message that will be shown on the user screen whenever their message is blocked.

```csharp
[JsonProperty("custom_message", NullValueHandling = NullValueHandling.Ignore)]
public string? CustomMessage { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_Entities_DiscordRuleActionMetadata_TimeoutSeconds"></a>TimeoutSeconds

Gets the timeout duration in seconds.

```csharp
[JsonIgnore]
public TimeSpan TimeoutSeconds { get; }
```

#### Property Value

[TimeSpan](https://learn.microsoft.com/dotnet/api/system.timespan)

