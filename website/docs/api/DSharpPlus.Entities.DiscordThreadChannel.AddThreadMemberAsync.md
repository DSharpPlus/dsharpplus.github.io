# Method AddThreadMemberAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordThreadChannel_AddThreadMemberAsync_DSharpPlus_Entities_DiscordMember_"></a>AddThreadMemberAsync\(DiscordMember\)

Adds the given DiscordMember to this thread. Requires an not archived thread and send message permissions.

```csharp
public Task AddThreadMemberAsync(DiscordMember member)
```

### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to add to the thread.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.SendMessages" data-throw-if-not-resolved="false"></xref>.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

