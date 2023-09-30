# Method AddDmRecipientAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordDmChannel_AddDmRecipientAsync_System_UInt64_System_String_System_String_"></a>AddDmRecipientAsync\(ulong, string, string\)

Only use for Group DMs! Whitelisted bots only. Requires user's oauth2 access token

```csharp
public Task AddDmRecipientAsync(ulong user_id, string accesstoken, string nickname)
```

### Parameters

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the user to add.

`accesstoken` [string](https://learn.microsoft.com/dotnet/api/system.string)

The OAuth2 access token.

`nickname` [string](https://learn.microsoft.com/dotnet/api/system.string)

The nickname to give to the user.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the channel does not exist.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

