# Method ModifyCurrentMemberAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyCurrentMemberAsync_System_UInt64_System_String_System_String_"></a>ModifyCurrentMemberAsync\(ulong, string, string\)

Changes the current user in a guild.

```csharp
public Task ModifyCurrentMemberAsync(ulong guild_id, string nickname, string reason)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

Nickname to set

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Audit log reason

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

