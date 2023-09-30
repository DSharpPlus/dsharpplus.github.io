# Method ModifyGuildMemberAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyGuildMemberAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_Optional_System_String__DSharpPlus_Entities_Optional_System_Collections_Generic_IEnumerable_System_UInt64___DSharpPlus_Entities_Optional_System_Boolean__DSharpPlus_Entities_Optional_System_Boolean__DSharpPlus_Entities_Optional_System_Nullable_System_UInt64___DSharpPlus_Entities_Optional_System_Nullable_System_DateTimeOffset___System_String_"></a>ModifyGuildMemberAsync\(ulong, ulong, Optional<string\>, Optional<IEnumerable<ulong\>\>, Optional<bool\>, Optional<bool\>, Optional<ulong?\>, Optional<DateTimeOffset?\>, string\)

Modifies guild member.

```csharp
public Task ModifyGuildMemberAsync(ulong guild_id, ulong user_id, Optional<string> nick, Optional<IEnumerable<ulong>> role_ids, Optional<bool> mute, Optional<bool> deaf, Optional<ulong?> voice_channel_id, Optional<DateTimeOffset?> communication_disabled_until, string reason)
```

### Parameters

`guild\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Guild ID

`user\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

User ID

`nick` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New nickname

`role\_ids` [Optional](DSharpPlus.Entities.Optional\-1.md)<[IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>\>

New roles

`mute` [Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether this user should be muted

`deaf` [Optional](DSharpPlus.Entities.Optional\-1.md)<[bool](https://learn.microsoft.com/dotnet/api/system.boolean)\>

Whether this user should be deafened

`voice\_channel\_id` [Optional](DSharpPlus.Entities.Optional\-1.md)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?\>

Voice channel to move this user to

`communication\_disabled\_until` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)?\>

How long this member should be timed out for. Requires MODERATE_MEMBERS permission.

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason this user was modified

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

