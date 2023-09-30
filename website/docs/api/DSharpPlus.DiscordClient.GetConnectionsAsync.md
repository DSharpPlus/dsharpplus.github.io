# Method GetConnectionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetConnectionsAsync"></a>GetConnectionsAsync\(\)

Gets a list of connections

```csharp
public Task<IReadOnlyList<DiscordConnection>> GetConnectionsAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordConnection](DSharpPlus.Entities.DiscordConnection.md)\>\>

### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

