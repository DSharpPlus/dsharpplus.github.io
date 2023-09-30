# Method ModifyGuildIntegrationAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildIntegrationAsync_System_UInt64_System_UInt64_System_Int32_System_Int32_System_Boolean_"></a>ModifyGuildIntegrationAsync\(ulong, ulong, int, int, bool\)

Modifies a guild integration

```csharp
public Task<DiscordIntegration> ModifyGuildIntegrationAsync(ulong guild_id, ulong integration_id, int expire_behaviour, int expire_grace_period, bool enable_emoticons)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`integration\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Integration ID

`expire\_behaviour` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Expiration behaviour

`expire\_grace\_period` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Expiration grace period

`enable\_emoticons` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to enable emojis for this integration

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

