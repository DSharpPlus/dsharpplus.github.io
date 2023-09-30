# Method GetAllMembersAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetAllMembersAsync"></a>GetAllMembersAsync\(\)

Retrieves a full list of members from Discord. This method will bypass cache.

```csharp
public Task<IReadOnlyCollection<DiscordMember>> GetAllMembersAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyCollection](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlycollection\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>\>

A collection of all members in this guild.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

