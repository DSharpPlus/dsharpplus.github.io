# Method CrosspostMessageAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_CrosspostMessageAsync_DSharpPlus_Entities_DiscordMessage_"></a>CrosspostMessageAsync\(DiscordMessage\)

Publishes a message in a news channel to following channels

```csharp
public Task<DiscordMessage> CrosspostMessageAsync(DiscordMessage message)
```

### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

Message to publish

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when the message has already been crossposted

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> and/or <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref>

