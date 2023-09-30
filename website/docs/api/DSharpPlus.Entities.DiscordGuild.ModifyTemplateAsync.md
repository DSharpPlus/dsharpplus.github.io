# Method ModifyTemplateAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyTemplateAsync_System_String_System_String_System_String_"></a>ModifyTemplateAsync\(string, string, string\)

Modifies the template's metadata.

```csharp
public Task<DiscordGuildTemplate> ModifyTemplateAsync(string code, string name = null, string description = null)
```

### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The template's code.

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Name of the template.

`description` [string](https://learn.microsoft.com/dotnet/api/system.string)

Description of the template.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The template modified.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Throws when the template for the code cannot be found

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

