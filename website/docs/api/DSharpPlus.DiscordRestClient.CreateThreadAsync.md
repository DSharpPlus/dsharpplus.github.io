# Method CreateThreadAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateThreadAsync_System_UInt64_System_String_DSharpPlus_AutoArchiveDuration_DSharpPlus_ChannelType_System_String_"></a>CreateThreadAsync\(ulong, string, AutoArchiveDuration, ChannelType, string\)

Creates a thread.

```csharp
public Task<DiscordThreadChannel> CreateThreadAsync(ulong channelId, string name, AutoArchiveDuration archiveAfter, ChannelType threadType, string reason = null)
```

### Parameters

`channelId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the channel.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

The name of the thread.

`archiveAfter` [AutoArchiveDuration](DSharpPlus.AutoArchiveDuration.md)

The auto archive duration.

`threadType` [ChannelType](DSharpPlus.ChannelType.md)

The type of the thread.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannel](DSharpPlus.Entities.DiscordThreadChannel.md)\>

