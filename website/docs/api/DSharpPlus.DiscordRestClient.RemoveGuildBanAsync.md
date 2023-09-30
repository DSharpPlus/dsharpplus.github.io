# Method RemoveGuildBanAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_RemoveGuildBanAsync_System_UInt64_System_UInt64_System_String_"></a>RemoveGuildBanAsync\(ulong, ulong, string\)

Removes a guild ban

```csharp
public Task RemoveGuildBanAsync(ulong guild_id, ulong user_id, string reason)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User to unban

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this member was unbanned

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

