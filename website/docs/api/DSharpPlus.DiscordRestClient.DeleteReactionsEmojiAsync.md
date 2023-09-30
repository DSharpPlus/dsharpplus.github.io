# Method DeleteReactionsEmojiAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteReactionsEmojiAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteReactionsEmojiAsync\(ulong, ulong, string\)

Deletes all reactions of a specific reaction for a message.

```csharp
public Task DeleteReactionsEmojiAsync(ulong channelid, ulong messageId, string emoji)
```

### Parameters

`channelid` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message.

`emoji` [string](https://learn.microsoft.com/dotnet/api/system.string)

The emoji to clear.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

