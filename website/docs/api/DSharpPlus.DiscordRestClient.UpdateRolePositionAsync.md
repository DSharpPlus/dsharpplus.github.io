# Method UpdateRolePositionAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_UpdateRolePositionAsync_System_UInt64_System_UInt64_System_Int32_System_String_"></a>UpdateRolePositionAsync\(ulong, ulong, int, string\)

Updates a role's position

```csharp
public Task UpdateRolePositionAsync(ulong guild_id, ulong role_id, int position, string reason = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`role\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Role ID

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Role position

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this position was modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

