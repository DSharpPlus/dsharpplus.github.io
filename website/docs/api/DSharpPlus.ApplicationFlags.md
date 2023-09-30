# Enum ApplicationFlags

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

Represents flags for a discord application.

```csharp
public enum ApplicationFlags
```

###### Extension Methods

[ExtensionMethods.GetName<ApplicationFlags\>\(ApplicationFlags\)](DSharpPlus.SlashCommands.ExtensionMethods.md\#DSharpPlus\_SlashCommands\_ExtensionMethods\_GetName\_\_1\_\_\_0\_)

## Fields

`ApplicationAutoModerationRuleCreateBadge = 64` 

Indicates if an application uses the Auto Moderation API.

`ApplicationCommandBadge = 8388608` 

Indicates if an application has registered global application commands.

`Embedded = 131072` 

Indicates that the application is a voice channel application.

`GatewayGuildMembers = 16384` 

Indicates that the application is approved for the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent.

`GatewayGuildMembersLimited = 32768` 

Indicates that the application is awaiting approval for the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent.

`GatewayMessageContent = 262144` 

The application can track message content.

`GatewayMessageContentLimited = 524288` 

The application can track message content (limited).

`GatewayPresence = 4096` 

Indicates that the application is approved for the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent.

`GatewayPresenceLimited = 8192` 

Indicates that the application is awaiting approval for the <xref href="DSharpPlus.DiscordIntents.GuildPresences" data-throw-if-not-resolved="false"></xref> intent.

`VerificationPendingGuildLimit = 65536` 

Indicates that the application is awaiting verification.

