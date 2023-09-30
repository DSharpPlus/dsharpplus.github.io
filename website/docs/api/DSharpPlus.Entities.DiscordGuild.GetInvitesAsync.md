# Method GetInvitesAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetInvitesAsync"></a>GetInvitesAsync\(\)

Gets all the invites created for all the channels in this guild.

```csharp
public Task<IReadOnlyList<DiscordInvite>> GetInvitesAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>\>

A collection of invites.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

