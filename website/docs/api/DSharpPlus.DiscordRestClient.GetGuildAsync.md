# Method GetGuildAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildAsync_System_UInt64_System_Nullable_System_Boolean__"></a>GetGuildAsync\(ulong, bool?\)

Gets a guild.

```csharp
public Task<DiscordGuild> GetGuildAsync(ulong guild_id, bool? with_counts = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID to search for.

`with\_counts` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to include approximate presence and member counts in the returned guild.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

