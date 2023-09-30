# Method ModifyRolePositionsAsync

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordGuild_ModifyRolePositionsAsync_System_Collections_Generic_IDictionary_System_Int32_DSharpPlus_Entities_DiscordRole__System_String_"></a>ModifyRolePositionsAsync\(IDictionary<int, DiscordRole\>, string\)

Batch modifies the role order in the guild.

```csharp
public Task<IReadOnlyList<DiscordRole>> ModifyRolePositionsAsync(IDictionary<int, DiscordRole> roles, string reason = null)
```

### Parameters

`roles` [IDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.idictionary\-2)<[int](https://learn.microsoft.com/dotnet/api/system.int32), [DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

A dictionary of guild roles indexed by their new role positions.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

An optional Audit log reason on why this action was done.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>\>

A list of all the current guild roles ordered in their new role positions.

