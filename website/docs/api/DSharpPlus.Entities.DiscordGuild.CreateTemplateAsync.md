# Method CreateTemplateAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_CreateTemplateAsync_System_String_System_String_"></a>CreateTemplateAsync\(string, string\)

Creates a guild template.

```csharp
public Task<DiscordGuildTemplate> CreateTemplateAsync(string name, string description = null)
```

### Parameters

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template created.

### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Throws when a template already exists for the guild or a null parameter is provided for the name.

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

