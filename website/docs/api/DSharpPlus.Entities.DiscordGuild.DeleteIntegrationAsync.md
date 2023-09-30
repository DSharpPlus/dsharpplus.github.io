# Method DeleteIntegrationAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_DeleteIntegrationAsync_DSharpPlus_Entities_DiscordIntegration_System_String_"></a>DeleteIntegrationAsync\(DiscordIntegration, string?\)

Removes an integration from this guild.

```csharp
public Task DeleteIntegrationAsync(DiscordIntegration integration, string? reason = null)
```

### Parameters

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to remove.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

