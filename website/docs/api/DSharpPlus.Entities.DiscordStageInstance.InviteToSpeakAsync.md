# Method InviteToSpeakAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordStageInstance_InviteToSpeakAsync_DSharpPlus_Entities_DiscordMember_"></a>InviteToSpeakAsync\(DiscordMember\)

Invite a member to become a speaker in the state instance.

```csharp
public Task InviteToSpeakAsync(DiscordMember member)
```

### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

The member to invite to speak on stage.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.MoveMembers" data-throw-if-not-resolved="false"></xref> permission

