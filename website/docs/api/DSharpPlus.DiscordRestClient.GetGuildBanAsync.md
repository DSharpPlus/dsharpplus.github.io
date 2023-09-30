# Method GetGuildBanAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildBanAsync_System_UInt64_System_UInt64_"></a>GetGuildBanAsync\(ulong, ulong\)

Gets the ban of the specified user. Requires Ban Members permission.

```csharp
public Task<DiscordBan> GetGuildBanAsync(ulong guild_id, ulong user_id)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild to get the ban from.

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the user to get the ban for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>

A guild ban object.

