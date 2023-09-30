# Method CreateGuildRoleAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateGuildRoleAsync_System_UInt64_System_String_System_Nullable_DSharpPlus_Permissions__System_Nullable_System_Int32__System_Nullable_System_Boolean__System_Nullable_System_Boolean__System_String_System_IO_Stream_DSharpPlus_Entities_DiscordEmoji_"></a>CreateGuildRoleAsync\(ulong, string, Permissions?, int?, bool?, bool?, string, Stream, DiscordEmoji\)

Creates a new role

```csharp
public Task<DiscordRole> CreateGuildRoleAsync(ulong guild_id, string name, Permissions? permissions, int? color, bool? hoist, bool? mentionable, string reason, Stream icon = null, DiscordEmoji emoji = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`name` [string](https://learn.microsoft.com/dotnet/api/system.string)

Role name

`permissions` [Permissions](DSharpPlus.Permissions.md)?

Role permissions

`color` [int](https://learn.microsoft.com/dotnet/api/system.int32)?

Role color

`hoist` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be hoisted

`mentionable` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether this role should be mentionable

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why this role was created

`icon` [Stream](https://learn.microsoft.com/dotnet/api/system.io.stream)

The icon to add to this role

`emoji` [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

The emoji to add to this role. Must be unicode.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

