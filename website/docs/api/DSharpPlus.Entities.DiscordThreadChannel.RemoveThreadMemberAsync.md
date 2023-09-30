# Method RemoveThreadMemberAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordThreadChannel_RemoveThreadMemberAsync_DSharpPlus_Entities_DiscordMember_"></a>RemoveThreadMemberAsync\(DiscordMember\)

Removes the given DiscordMember from this thread. Requires an not archived thread and send message permissions.

```csharp
public Task RemoveThreadMemberAsync(DiscordMember member)
```

### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to remove from the thread.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageThreads" data-throw-if-not-resolved="false"></xref> permission, or is not the creator of the thread if it is private.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

