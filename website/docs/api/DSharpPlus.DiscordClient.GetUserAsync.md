# Method GetUserAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_DiscordClient_GetUserAsync_System_UInt64_System_Boolean_"></a>GetUserAsync\(ulong, bool\)

Gets a user

```csharp
public Task<DiscordUser> GetUserAsync(ulong userId, bool updateCache = false)
```

### Parameters

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the user

`updateCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request and update cache. Passing true will update the user, updating stale properties such as <xref href="DSharpPlus.Entities.DiscordUser.BannerHash" data-throw-if-not-resolved="false"></xref>.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

### Exceptions

[BadRequestException](DSharpPlus.Exceptions.BadRequestException.md)

Thrown when an invalid parameter was provided.

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

