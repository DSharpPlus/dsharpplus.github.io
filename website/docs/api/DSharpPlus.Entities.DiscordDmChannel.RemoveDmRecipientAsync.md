# Method RemoveDmRecipientAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordDmChannel_RemoveDmRecipientAsync_System_UInt64_System_String_"></a>RemoveDmRecipientAsync\(ulong, string\)

Only use for Group DMs!

```csharp
public Task RemoveDmRecipientAsync(ulong user_id, string accesstoken)
```

### Parameters

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the User to remove.

`accesstoken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The OAuth2 access token.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

