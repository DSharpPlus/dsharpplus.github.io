# Method EditChannelPermissionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_EditChannelPermissionsAsync_System_UInt64_System_UInt64_DSharpPlus_Permissions_DSharpPlus_Permissions_System_String_System_String_"></a>EditChannelPermissionsAsync\(ulong, ulong, Permissions, Permissions, string, string\)

Edits channel overwrite

```csharp
public Task EditChannelPermissionsAsync(ulong channel_id, ulong overwrite_id, Permissions allow, Permissions deny, string type, string reason)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`overwrite\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Overwrite ID

`allow` [Permissions](DSharpPlus.Permissions.md)

Permissions to allow

`deny` [Permissions](DSharpPlus.Permissions.md)

Permissions to deny

`type` [string](https://learn.microsoft.com/dotnet/api/system.string)

Overwrite type

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this overwrite was created

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

