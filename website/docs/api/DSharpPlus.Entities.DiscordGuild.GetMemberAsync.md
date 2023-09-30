# Method GetMemberAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetMemberAsync_System_UInt64_System_Boolean_"></a>GetMemberAsync\(ulong, bool\)

Gets a member of this guild by their user ID.

```csharp
public Task<DiscordMember> GetMemberAsync(ulong userId, bool updateCache = false)
```

### Parameters

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

ID of the member to get.

`updateCache` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to always make a REST request and update the member cache.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

The requested member.

### Exceptions

[ServerErrorException](DSharpPlus.Exceptions.ServerErrorException.md)

Thrown when Discord is unable to process the request.

