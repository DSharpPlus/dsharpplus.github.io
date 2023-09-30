# Property LastMessageId

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordPartialChannel_LastMessageId"></a>LastMessageId

Gets the ID of the last message sent in this channel. This is applicable to text channels only.

```csharp
[JsonProperty("last_message_id", NullValueHandling = NullValueHandling.Ignore)]
public ulong? LastMessageId { get; }
```

### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

### Remarks

For forum posts, this ID may point to an invalid message (e.g. the OP deleted the initial forum message).

