# Method AddMemberAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_AddMemberAsync_DSharpPlus_Entities_DiscordUser_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_Boolean_System_Boolean_"></a>AddMemberAsync\(DiscordUser, string, string, IEnumerable<DiscordRole\>, bool, bool\)

Adds a new member to this guild

```csharp
public Task AddMemberAsync(DiscordUser user, string access_token, string nickname = null, IEnumerable<DiscordRole> roles = null, bool muted = false, bool deaf = false)
```

### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

User to add

`access\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

User's access token (OAuth2)

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

new nickname

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

new roles

`muted` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

whether this user has to be muted

`deaf` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

whether this user has to be deafened

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.CreateInstantInvite" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the <code class="paramref">user</code> or <code class="paramref">access_token</code> is not found.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

