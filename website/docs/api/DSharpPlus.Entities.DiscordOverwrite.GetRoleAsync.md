# Method GetRoleAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordOverwrite_GetRoleAsync"></a>GetRoleAsync\(\)

Gets the DiscordRole that is affected by this overwrite.

```csharp
public Task<DiscordRole> GetRoleAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

The DiscordRole that is affected by this overwrite

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the role does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

