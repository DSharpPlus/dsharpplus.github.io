# Method CreateInviteAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_CreateInviteAsync_System_Int32_System_Int32_System_Boolean_System_Boolean_System_String_System_Nullable_DSharpPlus_InviteTargetType__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>CreateInviteAsync\(int, int, bool, bool, string, InviteTargetType?, ulong?, ulong?\)

Create a new invite object

```csharp
public Task<DiscordInvite> CreateInviteAsync(int max_age = 86400, int max_uses = 0, bool temporary = false, bool unique = false, string reason = null, InviteTargetType? targetType = null, ulong? targetUserId = null, ulong? targetApplicationId = null)
```

### Parameters

`max\_age` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Duration of invite in seconds before expiry, or 0 for never.  Defaults to 86400.

`max\_uses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Max number of uses or 0 for unlimited.  Defaults to 0

`temporary` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this invite only grants temporary membership.  Defaults to false.

`unique` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

If true, don't try to reuse a similar invite (useful for creating many unique one time use invites)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

`targetType` [InviteTargetType](DSharpPlus.InviteTargetType.md)?

The target type of the invite, for stream and embedded application invites.

`targetUserId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target user.

`targetApplicationId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target application.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.CreateInstantInvite" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

