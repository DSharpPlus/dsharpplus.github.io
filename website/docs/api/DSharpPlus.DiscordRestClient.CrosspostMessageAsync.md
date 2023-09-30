# Method CrosspostMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CrosspostMessageAsync_System_UInt64_System_UInt64_"></a>CrosspostMessageAsync\(ulong, ulong\)

Publishes a message in a news channel to following channels

```csharp
public Task<DiscordMessage> CrosspostMessageAsync(ulong channel_id, ulong message_id)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the news channel the message to crosspost belongs to

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the message to crosspost

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> and/or <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref>

