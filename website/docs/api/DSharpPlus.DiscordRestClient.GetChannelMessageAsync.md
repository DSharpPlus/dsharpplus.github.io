# Method GetChannelMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_GetChannelMessageAsync_System_UInt64_System_UInt64_"></a>GetChannelMessageAsync\(ulong, ulong\)

Gets a message from a channel

```csharp
public Task<DiscordMessage> GetChannelMessageAsync(ulong channel_id, ulong message_id)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

