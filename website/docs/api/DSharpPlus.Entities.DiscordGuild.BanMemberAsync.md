# Method BanMemberAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_BanMemberAsync_DSharpPlus_Entities_DiscordMember_System_Int32_System_String_"></a>BanMemberAsync\(DiscordMember, int, string\)

Bans a specified member from this guild.

```csharp
public Task BanMemberAsync(DiscordMember member, int delete_message_days = 0, string reason = null)
```

### Parameters

`member` [DiscordMember](DSharpPlus.Entities.DiscordMember.md)

Member to ban.

`delete\_message\_days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How many days to remove messages from.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.BanMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

## <a id="DSharpPlus_Entities_DiscordGuild_BanMemberAsync_System_UInt64_System_Int32_System_String_"></a>BanMemberAsync\(ulong, int, string\)

Bans a specified user by ID. This doesn't require the user to be in this guild.

```csharp
public Task BanMemberAsync(ulong user_id, int delete_message_days = 0, string reason = null)
```

### Parameters

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the user to ban.

`delete\_message\_days` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How many days to remove messages from.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.BanMembers" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the member does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

