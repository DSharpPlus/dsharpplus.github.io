# Method ConnectAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_ConnectAsync_DSharpPlus_Entities_DiscordActivity_System_Nullable_DSharpPlus_Entities_UserStatus__System_Nullable_System_DateTimeOffset__"></a>ConnectAsync\(DiscordActivity, UserStatus?, DateTimeOffset?\)

Connects to the gateway

```csharp
public Task ConnectAsync(DiscordActivity activity = null, UserStatus? status = null, DateTimeOffset? idlesince = null)
```

### Parameters

`activity` [DiscordActivity](DSharpPlus.Entities.DiscordActivity.md)

`status` [UserStatus](DSharpPlus.Entities.UserStatus.md)?

`idlesince` [DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### Exceptions

[UnauthorizedException](DSharpPlus.Exceptions.UnauthorizedException.md)

Thrown when an invalid token was provided.

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

