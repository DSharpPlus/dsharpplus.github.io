# Method ModifyGuildMembershipScreeningFormAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildMembershipScreeningFormAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_MembershipScreeningEditModel__"></a>ModifyGuildMembershipScreeningFormAsync\(ulong, Action<MembershipScreeningEditModel\>\)

Modifies a guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> ModifyGuildMembershipScreeningFormAsync(ulong guild_id, Action<MembershipScreeningEditModel> action)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[MembershipScreeningEditModel](DSharpPlus.Net.Models.MembershipScreeningEditModel.md)\>

Action to perform

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

The modified screening form.

