# Method GetPruneCountAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetPruneCountAsync_System_Int32_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__"></a>GetPruneCountAsync\(int, IEnumerable<DiscordRole\>\)

Estimates the number of users to be pruned.

```csharp
public Task<int> GetPruneCountAsync(int days = 7, IEnumerable<DiscordRole> includedRoles = null)
```

### Parameters

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Minimum number of inactivity days required for users to be pruned. Defaults to 7.

`includedRoles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The roles to be included in the prune.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)\>

Number of users that will be pruned.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.KickMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

