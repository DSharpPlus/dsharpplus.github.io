# Property PerUserRateLimit

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_PerUserRateLimit"></a>PerUserRateLimit

<p>Gets the slow mode delay configured for this channel.</p>
<p>All bots, as well as users with <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> or <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permissions in the channel are exempt from slow mode.</p>

```csharp
[JsonProperty("rate_limit_per_user")]
public int? PerUserRateLimit { get; }
```

### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

