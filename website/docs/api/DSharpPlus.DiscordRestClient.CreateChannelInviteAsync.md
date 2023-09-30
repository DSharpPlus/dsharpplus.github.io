# Method CreateChannelInviteAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateChannelInviteAsync_System_UInt64_System_Int32_System_Int32_System_Boolean_System_Boolean_System_String_System_Nullable_DSharpPlus_InviteTargetType__System_Nullable_System_UInt64__System_Nullable_System_UInt64__"></a>CreateChannelInviteAsync\(ulong, int, int, bool, bool, string, InviteTargetType?, ulong?, ulong?\)

Creates a channel invite

```csharp
public Task<DiscordInvite> CreateChannelInviteAsync(ulong channel_id, int max_age, int max_uses, bool temporary, bool unique, string reason, InviteTargetType? targetType = null, ulong? targetUserId = null, ulong? targetApplicationId = null)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`max\_age` [int](https://learn.microsoft.com/dotnet/api/system.int32)

For how long the invite should exist

`max\_uses` [int](https://learn.microsoft.com/dotnet/api/system.int32)

How often the invite may be used

`temporary` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this invite should be temporary

`unique` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether this invite should be unique (false might return an existing invite)

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why you made an invite

`targetType` [InviteTargetType](DSharpPlus.InviteTargetType.md)?

The target type of the invite, for stream and embedded application invites.

`targetUserId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target user.

`targetApplicationId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the target application.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordInvite](DSharpPlus.Entities.DiscordInvite.md)\>

