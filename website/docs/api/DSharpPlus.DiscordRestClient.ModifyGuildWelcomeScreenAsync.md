# Method ModifyGuildWelcomeScreenAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildWelcomeScreenAsync_System_UInt64_System_Action_DSharpPlus_Net_Models_WelcomeScreenEditModel__System_String_"></a>ModifyGuildWelcomeScreenAsync\(ulong, Action<WelcomeScreenEditModel\>, string\)

Modifies a guild's welcome screen.

```csharp
public Task<DiscordGuildWelcomeScreen> ModifyGuildWelcomeScreenAsync(ulong guildId, Action<WelcomeScreenEditModel> action, string reason = null)
```

### Parameters

`guildId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The guild ID to modify.

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[WelcomeScreenEditModel](DSharpPlus.Net.Models.WelcomeScreenEditModel.md)\>

Action to perform.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

The audit log reason for this action.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildWelcomeScreen](DSharpPlus.Entities.DiscordGuildWelcomeScreen.md)\>

The modified welcome screen.

