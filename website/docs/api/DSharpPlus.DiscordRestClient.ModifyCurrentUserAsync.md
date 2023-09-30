# Method ModifyCurrentUserAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyCurrentUserAsync_System_String_System_String_"></a>ModifyCurrentUserAsync\(string, string\)

Modifies current user

```csharp
public Task<DiscordUser> ModifyCurrentUserAsync(string username, string base64_avatar)
```

### Parameters

`username` [string](https://learn.microsoft.com/dotnet/api/system.string)

New username

`base64\_avatar` [string](https://learn.microsoft.com/dotnet/api/system.string)

New avatar (base64)

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

## <a id="DSharpPlus_DiscordRestClient_ModifyCurrentUserAsync_System_String_System_IO_Stream_"></a>ModifyCurrentUserAsync\(string, Stream\)

Modifies current user

```csharp
public Task<DiscordUser> ModifyCurrentUserAsync(string username = null, Stream avatar = null)
```

### Parameters

`username` [string](https://learn.microsoft.com/dotnet/api/system.string)

username

`avatar` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

avatar

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

