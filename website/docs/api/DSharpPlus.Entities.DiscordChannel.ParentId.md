# Property ParentId

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_ParentId"></a>ParentId

Gets ID of the category that contains this channel. For threads, gets the ID of the channel this thread was created in.

```csharp
[JsonProperty("parent_id", NullValueHandling = NullValueHandling.Include)]
public ulong? ParentId { get; }
```

### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

