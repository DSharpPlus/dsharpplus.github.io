# Property ExemptChannels

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordAutoModerationRule_ExemptChannels"></a>ExemptChannels

Gets ids of channels in which rule will be not triggered.

```csharp
[JsonProperty("exempt_channels", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<ulong>? ExemptChannels { get; }
```

### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>?

### Remarks

Maximum of 50.

