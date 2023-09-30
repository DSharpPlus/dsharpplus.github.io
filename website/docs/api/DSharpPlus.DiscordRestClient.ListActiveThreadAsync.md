# Method ListActiveThreadAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ListActiveThreadAsync_System_UInt64_"></a>ListActiveThreadAsync\(ulong\)

Lists the active threads of a guild.

```csharp
public Task<ThreadQueryResult> ListActiveThreadAsync(ulong guildId)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the guild.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

