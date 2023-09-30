# Method CreateGuildIntegrationAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildIntegrationAsync_System_UInt64_System_String_System_UInt64_"></a>CreateGuildIntegrationAsync\(ulong, string, ulong\)

Creates guild integration

```csharp
public Task<DiscordIntegration> CreateGuildIntegrationAsync(ulong guild_id, string type, ulong id)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`type` [string](https://learn.microsoft.com/dotnet/api/system.string)

Integration type

`id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Integration id

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

