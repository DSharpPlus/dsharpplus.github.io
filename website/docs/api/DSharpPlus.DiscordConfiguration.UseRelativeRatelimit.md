# Property UseRelativeRatelimit

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordConfiguration_UseRelativeRatelimit"></a>UseRelativeRatelimit

<p>Sets whether to rely on Discord for NTP (Network Time Protocol) synchronization with the "X-Ratelimit-Reset-After" header.</p>
<p>If the system clock is not synced, setting this to true will ensure ratelimits are synced with Discord and reduce the risk of hitting one.</p>
<p>This should only be set to false if the system clock is synced with NTP.</p>
<p>Defaults to true.</p>

```csharp
public bool UseRelativeRatelimit { set; }
```

### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

