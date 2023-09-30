# Method GetReactionsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessage_GetReactionsAsync_DSharpPlus_Entities_DiscordEmoji_System_Int32_System_Nullable_System_UInt64__"></a>GetReactionsAsync\(DiscordEmoji, int, ulong?\)

Gets users that reacted with this emoji.

```csharp
public Task<IReadOnlyList<DiscordUser>> GetReactionsAsync(DiscordEmoji emoji, int limit = 25, ulong? after = null)
```

### Parameters

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

Emoji to react with.

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Limit of users to fetch.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Fetch users after this user's id.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the emoji does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

