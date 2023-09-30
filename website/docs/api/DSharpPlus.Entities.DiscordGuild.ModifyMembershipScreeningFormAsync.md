# Method ModifyMembershipScreeningFormAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyMembershipScreeningFormAsync_System_Action_DSharpPlus_Net_Models_MembershipScreeningEditModel__"></a>ModifyMembershipScreeningFormAsync\(Action<MembershipScreeningEditModel\>\)

Modifies this guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> ModifyMembershipScreeningFormAsync(Action<MembershipScreeningEditModel> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[MembershipScreeningEditModel](DSharpPlus.Net.Models.MembershipScreeningEditModel.md)\>

Action to perform

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

The modified screening form.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client doesn't have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission, or community is not enabled on this guild.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

