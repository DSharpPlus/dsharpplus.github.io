# Method ModifyPositionAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_ModifyPositionAsync_System_Int32_System_String_System_Nullable_System_Boolean__System_Nullable_System_UInt64__"></a>ModifyPositionAsync\(int, string, bool?, ulong?\)

Updates the channel position

```csharp
public Task ModifyPositionAsync(int position, string reason = null, bool? lockPermissions = null, ulong? parentId = null)
```

### Parameters

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Position the channel should be moved to.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

`lockPermissions` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to sync channel permissions with the parent, if moving to a new category.

`parentId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The new parent ID if the channel is to be moved to a new category.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageChannels" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

