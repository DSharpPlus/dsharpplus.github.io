# Method AddGuildMemberRoleAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_AddGuildMemberRoleAsync_System_UInt64_System_UInt64_System_UInt64_System_String_"></a>AddGuildMemberRoleAsync\(ulong, ulong, ulong, string\)

Add role to guild member

```csharp
public Task AddGuildMemberRoleAsync(ulong guild_id, ulong user_id, ulong role_id, string reason)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this role gets added

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

