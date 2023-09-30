# Method ModifyIntegrationAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyIntegrationAsync_DSharpPlus_Entities_DiscordIntegration_System_Int32_System_Int32_System_Boolean_"></a>ModifyIntegrationAsync\(DiscordIntegration, int, int, bool\)

Modifies an integration in this guild.

```csharp
public Task<DiscordIntegration> ModifyIntegrationAsync(DiscordIntegration integration, int expireBehaviour, int expireGracePeriod, bool enableEmoticons)
```

### Parameters

`integration` [DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)

Integration to modify.

`expireBehaviour` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Number of days after which the integration expires.

`expireGracePeriod` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Length of grace period which allows for renewing the integration.

`enableEmoticons` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether emotes should be synced from this integration.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordIntegration](DSharpPlus.Entities.DiscordIntegration.md)\>

The modified integration.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the guild does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

