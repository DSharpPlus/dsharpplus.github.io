# Method CreateGuildBanAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildBanAsync_System_UInt64_System_UInt64_System_Int32_System_String_"></a>CreateGuildBanAsync\(ulong, ulong, int, string\)

Creates guild ban

```csharp
public Task CreateGuildBanAsync(ulong guild_id, ulong user_id, int delete_message_days, string reason)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`delete\_message\_days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Days to delete messages

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this member was banned

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

