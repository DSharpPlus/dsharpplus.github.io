# Method GetBanAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_GetBanAsync_System_UInt64_"></a>GetBanAsync\(ulong\)

Gets a ban for a specific user.

```csharp
public Task<DiscordBan> GetBanAsync(ulong userId)
```

### Parameters

`userId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the user to get the ban for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>

The requested ban object.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the specified user is not banned.

## <a id="DSharpPlus_Entities_DiscordGuild_GetBanAsync_DSharpPlus_Entities_DiscordUser_"></a>GetBanAsync\(DiscordUser\)

Gets a ban for a specific user.

```csharp
public Task<DiscordBan> GetBanAsync(DiscordUser user)
```

### Parameters

`user` [DiscordUser](DSharpPlus.Entities.DiscordUser.md)

The user to get the ban for.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordBan](DSharpPlus.Entities.DiscordBan.md)\>

The requested ban object.

### Exceptions

[NotFoundException](DSharpPlus.Exceptions.NotFoundException.md)

Thrown when the specified user is not banned.

