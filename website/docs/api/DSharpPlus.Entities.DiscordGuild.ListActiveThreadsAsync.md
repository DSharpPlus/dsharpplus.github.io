# Method ListActiveThreadsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ListActiveThreadsAsync"></a>ListActiveThreadsAsync\(\)

Gets the active and private threads for this guild.

```csharp
public Task<ThreadQueryResult> ListActiveThreadsAsync()
```

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

A list of all the active and private threads the user can access in the server.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

