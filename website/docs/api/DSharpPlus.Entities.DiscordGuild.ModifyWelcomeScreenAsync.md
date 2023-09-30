# Method ModifyWelcomeScreenAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyWelcomeScreenAsync_System_Action_DSharpPlus_Net_Models_WelcomeScreenEditModel__System_String_"></a>ModifyWelcomeScreenAsync\(Action<WelcomeScreenEditModel\>, string\)

Modifies this guild's welcome screen.

```csharp
public Task<DiscordGuildWelcomeScreen> ModifyWelcomeScreenAsync(Action<WelcomeScreenEditModel> action, string reason = null)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[WelcomeScreenEditModel](DSharpPlus.Net.Models.WelcomeScreenEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit log.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)\>

The modified welcome screen.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client doesn't have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission, or community is not enabled on this guild.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

