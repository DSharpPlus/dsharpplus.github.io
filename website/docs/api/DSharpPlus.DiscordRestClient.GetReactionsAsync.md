# Method GetReactionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetReactionsAsync_System_UInt64_System_UInt64_System_String_System_Nullable_System_UInt64__System_Int32_"></a>GetReactionsAsync\(ulong, ulong, string, ulong?, int\)

Gets all users that reacted with a specific emoji to a message

```csharp
public Task<IReadOnlyList<DiscordUser>> GetReactionsAsync(ulong channel_id, ulong message_id, string emoji, ulong? after_id = null, int limit = 25)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

Emoji to check for

`after\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Whether to search for reactions after this message id.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The maximum amount of reactions to fetch.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

## <a id="DSharpPlus_DiscordRestClient_GetReactionsAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_DiscordEmoji_System_Nullable_System_UInt64__System_Int32_"></a>GetReactionsAsync\(ulong, ulong, DiscordEmoji, ulong?, int\)

Gets all users that reacted with a specific emoji to a message

```csharp
public Task<IReadOnlyList<DiscordUser>> GetReactionsAsync(ulong channel_id, ulong message_id, DiscordEmoji emoji, ulong? after_id = null, int limit = 25)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji to check for

`after\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Whether to search for reactions after this message id.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

The maximum amount of reactions to fetch.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

