# Method CreateInteractionResponseAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateInteractionResponseAsync_System_UInt64_System_String_DSharpPlus_InteractionResponseType_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateInteractionResponseAsync\(ulong, string, InteractionResponseType, DiscordInteractionResponseBuilder\)

Creates a response to an interaction.

```csharp
public Task CreateInteractionResponseAsync(ulong interactionId, string interactionToken, InteractionResponseType type, DiscordInteractionResponseBuilder builder = null)
```

### Parameters

`interactionId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the interaction.

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The token of the interaction

`type` [InteractionResponseType](DSharpPlus.InteractionResponseType.md)

The type of the response.

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data, if any, to send.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

