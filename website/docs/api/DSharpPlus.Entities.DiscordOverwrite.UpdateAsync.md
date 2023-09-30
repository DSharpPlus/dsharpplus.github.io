# Method UpdateAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordOverwrite_UpdateAsync_System_Nullable_DSharpPlus_Permissions__System_Nullable_DSharpPlus_Permissions__System_String_"></a>UpdateAsync\(Permissions?, Permissions?, string\)

Updates this channel overwrite.

```csharp
public Task UpdateAsync(Permissions? allow = null, Permissions? deny = null, string reason = null)
```

### Parameters

`allow` [Permissions](DSharpPlus.Permissions.md)?

Permissions that are allowed.

`deny` [Permissions](DSharpPlus.Permissions.md)?

Permissions that are denied.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason as to why you made this change.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageRoles" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the overwrite does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

