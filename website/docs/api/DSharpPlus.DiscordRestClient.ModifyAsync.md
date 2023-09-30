# Method ModifyAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyAsync_System_UInt64_System_UInt64_System_Action_DSharpPlus_Net_Models_MemberEditModel__"></a>ModifyAsync\(ulong, ulong, Action<MemberEditModel\>\)

Modifies a member

```csharp
public Task ModifyAsync(ulong member_id, ulong guild_id, Action<MemberEditModel> action)
```

### Parameters

`member\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Member ID

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[MemberEditModel](DSharpPlus.Net.Models.MemberEditModel.md)\>

Modifications

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

