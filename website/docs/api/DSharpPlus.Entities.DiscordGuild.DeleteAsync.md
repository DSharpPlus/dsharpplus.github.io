# Method DeleteAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_DeleteAsync"></a>DeleteAsync\(\)

Deletes this guild. Requires the caller to be the owner of the guild.

```csharp
public Task DeleteAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client is not the owner of the guild.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

