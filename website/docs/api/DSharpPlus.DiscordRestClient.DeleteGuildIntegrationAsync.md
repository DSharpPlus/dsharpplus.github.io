# Method DeleteGuildIntegrationAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteGuildIntegrationAsync_System_UInt64_DSharpPlus_Entities_DiscordIntegration_System_String_"></a>DeleteGuildIntegrationAsync\(ulong, DiscordIntegration, string\)

Removes a guild integration

```csharp
public Task DeleteGuildIntegrationAsync(ulong guild_id, DiscordIntegration integration, string reason = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to remove

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this integration was removed

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

