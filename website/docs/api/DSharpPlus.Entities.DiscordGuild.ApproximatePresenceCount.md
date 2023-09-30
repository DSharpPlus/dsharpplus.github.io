# Property ApproximatePresenceCount

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ApproximatePresenceCount"></a>ApproximatePresenceCount

Gets the approximate number of presences in this guild, when using <xref href="DSharpPlus.DiscordClient.GetGuildAsync(System.UInt64%2cSystem.Nullable%7bSystem.Boolean%7d)" data-throw-if-not-resolved="false"></xref> and having <code class="paramref">withCounts</code> set to true.

```csharp
[JsonProperty("approximate_presence_count", NullValueHandling = NullValueHandling.Ignore)]
public int? ApproximatePresenceCount { get; }
```

### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

