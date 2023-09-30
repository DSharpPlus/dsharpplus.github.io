# Method CreateThreadFromMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateThreadFromMessageAsync_System_UInt64_System_UInt64_System_String_DSharpPlus_AutoArchiveDuration_System_String_"></a>CreateThreadFromMessageAsync\(ulong, ulong, string, AutoArchiveDuration, string\)

Creates a thread from a message.

```csharp
public Task<DiscordThreadChannel> CreateThreadFromMessageAsync(ulong channelId, ulong messageId, string name, AutoArchiveDuration archiveAfter, string reason = null)
```

### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

