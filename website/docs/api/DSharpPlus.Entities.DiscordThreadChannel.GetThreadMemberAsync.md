# Method GetThreadMemberAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordThreadChannel_GetThreadMemberAsync_DSharpPlus_Entities_DiscordMember_"></a>GetThreadMemberAsync\(DiscordMember\)

Returns a thread member object for the specified user if they are a member of the thread, returns a 404 response otherwise.

```csharp
public Task<DiscordThreadChannelMember> GetThreadMemberAsync(DiscordMember member)
```

### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The guild member to retrieve.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when a GuildMember has not joined the channel thread.

