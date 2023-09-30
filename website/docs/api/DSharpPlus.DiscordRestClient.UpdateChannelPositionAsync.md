# Method UpdateChannelPositionAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_UpdateChannelPositionAsync_System_UInt64_System_UInt64_System_Int32_System_String_System_Nullable_System_Boolean__System_Nullable_System_UInt64__"></a>UpdateChannelPositionAsync\(ulong, ulong, int, string, bool?, ulong?\)

Updates a channel's position

```csharp
public Task UpdateChannelPositionAsync(ulong guild_id, ulong channel_id, int position, string reason, bool? lockPermissions = null, ulong? parentId = null)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`position` [int](https://learn.microsoft.com/dotnet/api/system.int32)

Channel position

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this position was modified

`lockPermissions` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)?

Whether to sync channel permissions with the parent, if moving to a new category.

`parentId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The new parent id if the channel is to be moved to a new category.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

