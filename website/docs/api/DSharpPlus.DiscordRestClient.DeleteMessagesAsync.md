# Method DeleteMessagesAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteMessagesAsync_System_UInt64_System_Collections_Generic_IEnumerable_System_UInt64__System_String_"></a>DeleteMessagesAsync\(ulong, IEnumerable<ulong\>, string\)

Deletes multiple messages

```csharp
public Task DeleteMessagesAsync(ulong channel_id, IEnumerable<ulong> message_ids, string reason)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_ids` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)\>

Message IDs

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason these messages were deleted

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

