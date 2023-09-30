# Method DeleteMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_DeleteMessageAsync_System_UInt64_System_UInt64_System_String_"></a>DeleteMessageAsync\(ulong, ulong, string\)

Deletes a message

```csharp
public Task DeleteMessageAsync(ulong channel_id, ulong message_id, string reason)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`reason` [string](https://learn.microsoft.com/dotnet/api/system.string)

Why this message was deleted

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

