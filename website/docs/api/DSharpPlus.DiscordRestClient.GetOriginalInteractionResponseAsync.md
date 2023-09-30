# Method GetOriginalInteractionResponseAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetOriginalInteractionResponseAsync_System_String_"></a>GetOriginalInteractionResponseAsync\(string\)

Gets the original interaction response.

```csharp
public Task<DiscordMessage> GetOriginalInteractionResponseAsync(string interactionToken)
```

### Parameters

`interactionToken` [string](https://learn.microsoft.com/dotnet/api/system.string)

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The original message that was sent. This <b>does not work on ephemeral messages.</b>

