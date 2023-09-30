# Method GetMentionPrefixLength

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandsNextUtilities_GetMentionPrefixLength_DSharpPlus_Entities_DiscordMessage_DSharpPlus_Entities_DiscordUser_"></a>GetMentionPrefixLength\(DiscordMessage, DiscordUser\)

Checks whether the message contains a specified mention prefix.

```csharp
public static int GetMentionPrefixLength(this DiscordMessage msg, DiscordUser user)
```

### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to check.

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to check for.

### Returns

[int](https://learn.microsoft.com/dotnet/api/system.int32)

Positive number if the prefix is present, -1 otherwise.

