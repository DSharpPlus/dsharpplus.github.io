# Method ListThreadMembersAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ListThreadMembersAsync_System_UInt64_"></a>ListThreadMembersAsync\(ulong\)

Lists the members of a thread.

```csharp
public Task<IReadOnlyList<DiscordThreadChannelMember>> ListThreadMembersAsync(ulong threadId)
```

### Parameters

`threadId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the thread.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordThreadChannelMember](DSharpPlus.Entities.DiscordThreadChannelMember.md)\>\>

