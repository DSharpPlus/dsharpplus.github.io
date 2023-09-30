# Method GetChannelMessagesAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetChannelMessagesAsync_System_UInt64_System_Int32_System_Nullable_System_UInt64__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetChannelMessagesAsync\(ulong, int, ulong?, ulong?, ulong?\)

Gets messages from a channel

```csharp
public Task<IReadOnlyList<DiscordMessage>> GetChannelMessagesAsync(ulong channel_id, int limit, ulong? before, ulong? after, ulong? around)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit of messages to get

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets messages before this ID

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets messages after this ID

`around` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Gets messages around this ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>\>

