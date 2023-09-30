# Method DeleteTemplateAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_DeleteTemplateAsync_System_String_"></a>DeleteTemplateAsync\(string\)

Deletes the template.

```csharp
public Task<DiscordGuildTemplate> DeleteTemplateAsync(string code)
```

### Parameters

`code` [string](https://learn.microsoft.com/dotnet/api/system.string)

The code of the template to delete.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordGuildTemplate](DSharpPlus.Entities.DiscordGuildTemplate.md)\>

The deleted template.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Throws when the template for the code cannot be found

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Throws when the client does not have the <xref href="DSharpPlus.Permissions.ManageGuild" data-throw-if-not-resolved="false"></xref> permission.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

