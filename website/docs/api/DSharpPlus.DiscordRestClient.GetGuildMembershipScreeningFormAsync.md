# Method GetGuildMembershipScreeningFormAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetGuildMembershipScreeningFormAsync_System_UInt64_"></a>GetGuildMembershipScreeningFormAsync\(ulong\)

Gets a guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> GetGuildMembershipScreeningFormAsync(ulong guild_id)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

The guild's membership screening form.

