# Method DeleteAllReactionsAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteAllReactionsAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteAllReactionsAsync\(ulong, ulong, string\)

Deletes all reactions from a message

```csharp
public Task DeleteAllReactionsAsync(ulong channel_id, ulong message_id, string reason)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Reason why all reactions were removed

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

