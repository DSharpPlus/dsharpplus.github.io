# Class ThreadQueryResult

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

```csharp
public class ThreadQueryResult
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)

## Properties

### <a id="DSharpPlus_Entities_ThreadQueryResult_HasMore"></a>HasMore

Gets whether additional calls will yield more threads.

```csharp
[JsonProperty("has_more", NullValueHandling = NullValueHandling.Ignore)]
public bool HasMore { get; }
```

#### Property Value

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="DSharpPlus_Entities_ThreadQueryResult_Threads"></a>Threads

Gets the list of threads returned by the query. Generally ordered by <xref href="DSharpPlus.Entities.DiscordThreadChannelMetadata.ArchiveTimestamp" data-throw-if-not-resolved="false"></xref> in descending order.

```csharp
[JsonProperty("threads", NullValueHandling = NullValueHandling.Ignore)]
public IReadOnlyList<DiscordThreadChannel> Threads { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

