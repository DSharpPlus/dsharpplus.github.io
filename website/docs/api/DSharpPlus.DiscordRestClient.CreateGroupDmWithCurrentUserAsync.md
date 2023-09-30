# Method CreateGroupDmWithCurrentUserAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGroupDmWithCurrentUserAsync_System_Collections_Generic_IEnumerable_System_String__System_Collections_Generic_IDictionary_System_UInt64_System_String__"></a>CreateGroupDmWithCurrentUserAsync\(IEnumerable<string\>, IDictionary<ulong, string\>\)

Creates a group DM with current user

```csharp
public Task<DiscordDmChannel> CreateGroupDmWithCurrentUserAsync(IEnumerable<string> access_tokens, IDictionary<ulong, string> nicks)
```

### Parameters

`access\_tokens` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

Access tokens

`nicks` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [string](https://learn.microsoft.com/dotnet/api/system.string)\>

Nicknames

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordDmChannel](DSharpPlus.Entities.DiscordDmChannel.md)\>

