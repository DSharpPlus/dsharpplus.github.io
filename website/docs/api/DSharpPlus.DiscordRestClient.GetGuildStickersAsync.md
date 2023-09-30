# Method GetGuildStickersAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildStickersAsync_System_UInt64_"></a>GetGuildStickersAsync\(ulong\)

Gets a list of stickers from a guild.

```csharp
public Task<IReadOnlyList<DiscordMessageSticker>> GetGuildStickersAsync(ulong guildId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>\>

