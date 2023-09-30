# Method FollowAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_FollowAsync_DSharpPlus_Entities_DiscordChannel_"></a>FollowAsync\(DiscordChannel\)

Follows a news channel

```csharp
public Task<DiscordFollowedChannel> FollowAsync(DiscordChannel targetChannel)
```

### Parameters

`targetChannel` [DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

Channel to crosspost messages to

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordFollowedChannel](DSharpPlus.Entities.DiscordFollowedChannel.md)\>

### Exceptions

[ArgumentException](https://learn.microsoft.com/dotnet/api/system.argumentexception)

Thrown when trying to follow a non-news channel

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the current user doesn't have <xref href="DSharpPlus.Permissions.ManageWebhooks" data-throw-if-not-resolved="false"></xref> on the target channel

