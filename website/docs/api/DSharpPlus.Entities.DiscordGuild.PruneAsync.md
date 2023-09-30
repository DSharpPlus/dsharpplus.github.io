# Method PruneAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_PruneAsync_System_Int32_System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_String_"></a>PruneAsync\(int, bool, IEnumerable<DiscordRole\>, string\)

Prunes inactive users from this guild.

```csharp
public Task<int?> PruneAsync(int days = 7, bool computePruneCount = true, IEnumerable<DiscordRole> includedRoles = null, string reason = null)
```

### Parameters

`days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Minimum number of inactivity days required for users to be pruned. Defaults to 7.

`computePruneCount` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to return the prune count after this method completes. This is discouraged for larger guilds.

`includedRoles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The roles to be included in the prune.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[int](https://learn.microsoft.com/dotnet/api/system.int32)?\>

Number of users pruned.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

