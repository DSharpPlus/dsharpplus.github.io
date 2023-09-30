# Method GetBansAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetBansAsync_System_Nullable_System_Int32__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>GetBansAsync\(int?, ulong?, ulong?\)

Gets the bans for this guild.

```csharp
public Task<IReadOnlyList<DiscordBan>> GetBansAsync(int? limit = null, ulong? before = null, ulong? after = null)
```

### Parameters

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

The number of users to return (up to maximum 1000, default 1000).

`before` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users before the given user id.

`after` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

Consider only users after the given user id.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>\>

Collection of bans in this guild.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.BanMembers" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

