# Method AddGuildMemberAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_AddGuildMemberAsync_System_UInt64_System_UInt64_System_String_System_String_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordRole__System_Boolean_System_Boolean_"></a>AddGuildMemberAsync\(ulong, ulong, string, string, IEnumerable<DiscordRole\>, bool, bool\)

Adds a member to a guild

```csharp
public Task<DiscordMember> AddGuildMemberAsync(ulong guild_id, ulong user_id, string access_token, string nick, IEnumerable<DiscordRole> roles, bool muted, bool deafened)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`access\_token` [string](https://learn.microsoft.com/dotnet/api/system.string)

Access token

`nick` [string](https://learn.microsoft.com/dotnet/api/system.string)

User nickname

`roles` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

User roles

`muted` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this user should be muted on join

`deafened` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this user should be deafened on join

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMember](DSharpPlus.Entities.DiscordMember.md)\>

