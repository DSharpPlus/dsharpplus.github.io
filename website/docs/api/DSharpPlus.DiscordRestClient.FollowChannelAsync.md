# Method FollowChannelAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_FollowChannelAsync_System_UInt64_System_UInt64_"></a>FollowChannelAsync\(ulong, ulong\)

Follows a news channel

```csharp
public Task<DiscordFollowedChannel> FollowChannelAsync(ulong channel_id, ulong webhook_channel_id)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the channel to follow

`webhook\_channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the channel to crosspost messages to

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordFollowedChannel](DSharpPlus.Entities.DiscordFollowedChannel.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> on the target channel

