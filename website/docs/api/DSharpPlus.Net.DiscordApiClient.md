# Class DiscordApiClient

Namespace: [DSharpPlus.Net](DSharpPlus.Net.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class DiscordApiClient
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DiscordApiClient](DSharpPlus.Net.DiscordApiClient.md)

## Methods

### <a id="DSharpPlus_Net_DiscordApiClient_CreateForumPostAsync_System_UInt64_System_String_DSharpPlus_Entities_DiscordMessageBuilder_System_Nullable_DSharpPlus_AutoArchiveDuration__System_Nullable_System_Int32__System_Collections_Generic_IEnumerable_System_UInt64__"></a>CreateForumPostAsync\(ulong, string, DiscordMessageBuilder, AutoArchiveDuration?, int?, IEnumerable<ulong\>?\)

```csharp
public ValueTask<DiscordForumPostStarter> CreateForumPostAsync(ulong channelId, string name, DiscordMessageBuilder message, AutoArchiveDuration? autoArchiveDuration = null, int? rateLimitPerUser = null, IEnumerable<ulong>? appliedTags = null)
```

#### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

`message` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

`autoArchiveDuration` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)?

`rateLimitPerUser` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

`appliedTags` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>?

#### Returns

[ValueTask](https://learn.microsoft.com/dotnet/api/system.threading.tasks.valuetask\-1)<[DiscordForumPostStarter](DSharpPlus.Entities.DiscordForumPostStarter.md)\>

