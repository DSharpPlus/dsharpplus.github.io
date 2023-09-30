# Method GetMembershipScreeningFormAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetMembershipScreeningFormAsync"></a>GetMembershipScreeningFormAsync\(\)

Gets this guild's membership screening form.

```csharp
public Task<DiscordGuildMembershipScreening> GetMembershipScreeningFormAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildMembershipScreening](DSharpPlus.Entities.DiscordGuildMembershipScreening.md)\>

This guild's membership screening form.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

