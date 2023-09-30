# Method DeleteMessagesAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordChannel_DeleteMessagesAsync_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordMessage__System_String_"></a>DeleteMessagesAsync\(IEnumerable<DiscordMessage\>, string\)

Deletes multiple messages if they are less than 14 days old.  If they are older, none of the messages will be deleted and you will receive a <xref href="DSharpPlus.Exceptions.BadRequestException" data-throw-if-not-resolved="false"></xref> error.

```csharp
public Task DeleteMessagesAsync(IEnumerable<DiscordMessage> messages, string reason = null)
```

### Parameters

`messages` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

A collection of messages to delete.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason for audit logs.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when the client does not have the <xref href="DSharpPlus.Permissions.ManageMessages" data-throw-if-not-resolved="false"></xref> permission.

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

