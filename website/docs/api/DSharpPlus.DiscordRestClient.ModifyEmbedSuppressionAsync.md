# Method ModifyEmbedSuppressionAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_ModifyEmbedSuppressionAsync_System_UInt64_System_UInt64_System_Boolean_"></a>ModifyEmbedSuppressionAsync\(ulong, ulong, bool\)

Modifies the visibility of embeds in a message.

```csharp
public Task ModifyEmbedSuppressionAsync(ulong channel_id, ulong message_id, bool hideEmbeds)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`hideEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to hide all embeds.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

