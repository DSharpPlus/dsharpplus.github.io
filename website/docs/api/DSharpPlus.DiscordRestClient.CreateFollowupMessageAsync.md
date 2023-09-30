# Method CreateFollowupMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateFollowupMessageAsync_System_String_DSharpPlus_Entities_DiscordFollowupMessageBuilder_"></a>CreateFollowupMessageAsync\(string, DiscordFollowupMessageBuilder\)

Creates a follow up message to an interaction.

```csharp
public Task<DiscordMessage> CreateFollowupMessageAsync(string interactionToken, DiscordFollowupMessageBuilder builder)
```

### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction.

`builder` [DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

The webhook builder.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> created.

