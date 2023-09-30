# Method ListPrivateArchivedThreadsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_ListPrivateArchivedThreadsAsync_System_Nullable_System_DateTimeOffset__System_Int32_"></a>ListPrivateArchivedThreadsAsync\(DateTimeOffset?, int\)

Gets the threads that are private and archived for this channel.

```csharp
public Task<ThreadQueryResult> ListPrivateArchivedThreadsAsync(DateTimeOffset? before = null, int limit = 0)
```

### Parameters

`before` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

`limit` [int](https://learn.microsoft.com/dotnet/api/system.int32)

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[ThreadQueryResult](DSharpPlus.Entities.ThreadQueryResult.md)\>

A <xref href="DSharpPlus.Entities.ThreadQueryResult" data-throw-if-not-resolved="false"></xref> containing the threads for this query and if an other call will yield more threads.

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ReadMessageHistory" data-throw-if-not-resolved="false"></xref> and the <xref href="DSharpPlus.Permissions.ManageThreads" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

