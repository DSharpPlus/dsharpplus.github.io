# Property EditedTimestamp

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessage_EditedTimestamp"></a>EditedTimestamp

Gets the message's edit timestamp. Will be null if the message was not edited.

```csharp
[JsonProperty("edited_timestamp", NullValueHandling = NullValueHandling.Ignore)]
public DateTimeOffset? EditedTimestamp { get; }
```

### Property Value

[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

