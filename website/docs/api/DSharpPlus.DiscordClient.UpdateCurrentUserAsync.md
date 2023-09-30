# Method UpdateCurrentUserAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_UpdateCurrentUserAsync_System_String_DSharpPlus_Entities_Optional_System_IO_Stream__"></a>UpdateCurrentUserAsync\(string, Optional<Stream\>\)

Edits current user.

```csharp
public Task<DiscordUser> UpdateCurrentUserAsync(string username = null, Optional<Stream> avatar = default)
```

### Parameters

`username` [string](https://learn.microsoft.com/dotnet/api/system.string)

New username.

`avatar` [Optional](DSharpPlus.Entities.Optional\-1.md)<[Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)\>

New avatar.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the user does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

