# Method FollowUpAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_BaseContext_FollowUpAsync_DSharpPlus_Entities_DiscordFollowupMessageBuilder_"></a>FollowUpAsync\(DiscordFollowupMessageBuilder\)

Creates a follow up message to the interaction.

```csharp
public Task<DiscordMessage> FollowUpAsync(DiscordFollowupMessageBuilder builder)
```

### Parameters

`builder` [DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

The message to be sent, in the form of a webhook.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The created message.

