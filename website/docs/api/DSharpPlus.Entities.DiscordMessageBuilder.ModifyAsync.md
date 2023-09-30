# Method ModifyAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessageBuilder_ModifyAsync_DSharpPlus_Entities_DiscordMessage_"></a>ModifyAsync\(DiscordMessage\)

Sends the modified message.
<p>Note: Message replies cannot be modified. To clear the reply, simply pass <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/keywords/null">null</a> to <xref href="DSharpPlus.Entities.DiscordMessageBuilder.WithReply(System.Nullable%7bSystem.UInt64%7d%2cSystem.Boolean%2cSystem.Boolean)" data-throw-if-not-resolved="false"></xref>.</p>

```csharp
public Task<DiscordMessage> ModifyAsync(DiscordMessage msg)
```

### Parameters

`msg` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The original Message to modify.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The current builder to be chained.

