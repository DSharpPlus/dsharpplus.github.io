# Method GetGuildEmojisAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildEmojisAsync_System_UInt64_"></a>GetGuildEmojisAsync\(ulong\)

Gets a guild's emojis.

```csharp
public Task<IReadOnlyList<DiscordGuildEmoji>> GetGuildEmojisAsync(ulong guildId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordGuildEmoji](DSharpPlus.Entities.DiscordGuildEmoji.md)\>\>

