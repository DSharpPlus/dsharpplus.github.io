# Method SyncGuildTemplateAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_SyncGuildTemplateAsync_System_UInt64_System_String_"></a>SyncGuildTemplateAsync\(ulong, string\)

Syncs the template to the current guild's state.

```csharp
public Task<DiscordGuildTemplate> SyncGuildTemplateAsync(ulong guild_id, string code)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template to sync.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template synced.

