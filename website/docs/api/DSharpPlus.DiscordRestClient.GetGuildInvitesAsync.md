# Method GetGuildInvitesAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildInvitesAsync_System_UInt64_"></a>GetGuildInvitesAsync\(ulong\)

Get a guild's invites

```csharp
public Task<IReadOnlyList<DiscordInvite>> GetGuildInvitesAsync(ulong guild_id)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>\>

