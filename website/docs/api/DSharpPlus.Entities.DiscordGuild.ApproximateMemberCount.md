# Property ApproximateMemberCount

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ApproximateMemberCount"></a>ApproximateMemberCount

Gets the approximate number of members in this guild, when using <xref href="DSharpPlus.DiscordClient.GetGuildAsync(System.UInt64%2cSystem.Nullable%7bSystem.Boolean%7d)" data-throw-if-not-resolved="false"></xref> and having <code class="paramref">withCounts</code> set to true.

```csharp
[JsonProperty("approximate_member_count", NullValueHandling = NullValueHandling.Ignore)]
public int? ApproximateMemberCount { get; }
```

### Property Value

[int](https://learn.microsoft.com/dotnet/api/system.int32)?

