# Method GetEmojiAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetEmojiAsync_System_UInt64_"></a>GetEmojiAsync\(ulong\)

Gets this guild's specified custom emoji.

```csharp
public Task<DiscordGuildEmoji> GetEmojiAsync(ulong id)
```

### Parameters

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the emoji to get.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>

The requested custom emoji.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

