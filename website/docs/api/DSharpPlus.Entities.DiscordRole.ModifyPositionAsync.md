# Method ModifyPositionAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordRole_ModifyPositionAsync_System_Int32_System_String_"></a>ModifyPositionAsync\(int, string\)

Modifies this role's position.

```csharp
public Task ModifyPositionAsync(int position, string reason = null)
```

### Parameters

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

New position

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why we moved it

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

