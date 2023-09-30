# Method CreateResponseAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordInteraction_CreateResponseAsync_DSharpPlus_InteractionResponseType_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateResponseAsync\(InteractionResponseType, DiscordInteractionResponseBuilder\)

Creates a response to this interaction.

```csharp
public Task CreateResponseAsync(InteractionResponseType type, DiscordInteractionResponseBuilder builder = null)
```

### Parameters

`type` [InteractionResponseType](DSharpPlus.InteractionResponseType.md)

The type of the response.

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data, if any, to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

