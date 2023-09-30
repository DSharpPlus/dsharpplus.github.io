# Method ListJoinedMembersAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordThreadChannel_ListJoinedMembersAsync"></a>ListJoinedMembersAsync\(\)

Returns a full list of the thread members in this thread.
Requires the <xref href="DSharpPlus.DiscordIntents.GuildMembers" data-throw-if-not-resolved="false"></xref> intent specified in <xref href="DSharpPlus.DiscordConfiguration.Intents" data-throw-if-not-resolved="false"></xref>

```csharp
public Task<IReadOnlyList<DiscordThreadChannelMember>> ListJoinedMembersAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)\>\>

A collection of all threads members in this thread.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

