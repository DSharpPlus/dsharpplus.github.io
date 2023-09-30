# Method WithReply

Namespace: [DSharpPlus.Entities](DSharpPlus.Entities.md)  
Assembly: DSharpPlus.dll

## <a id="DSharpPlus_Entities_DiscordMessageBuilder_WithReply_System_Nullable_System_UInt64__System_Boolean_System_Boolean_"></a>WithReply\(ulong?, bool, bool\)

Sets if the message is a reply

```csharp
public DiscordMessageBuilder WithReply(ulong? messageId, bool mention = false, bool failOnInvalidReply = false)
```

### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)?

The ID of the message to reply to.

`mention` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

If we should mention the user in the reply.

`failOnInvalidReply` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether sending a reply that references an invalid message should be

### Returns

[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The current builder to be chained.

