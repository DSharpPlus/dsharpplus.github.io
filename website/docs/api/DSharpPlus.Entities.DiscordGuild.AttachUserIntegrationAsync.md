# Method AttachUserIntegrationAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_AttachUserIntegrationAsync_DSharpPlus_Entities_DiscordIntegration_"></a>AttachUserIntegrationAsync\(DiscordIntegration\)

Attaches an integration from current user to this guild.

```csharp
public Task<DiscordIntegration> AttachUserIntegrationAsync(DiscordIntegration integration)
```

### Parameters

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to attach.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

The integration after being attached to the guild.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

