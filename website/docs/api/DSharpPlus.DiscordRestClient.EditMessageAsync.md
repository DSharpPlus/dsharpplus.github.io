# Method EditMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_EditMessageAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_Optional_System_String__"></a>EditMessageAsync\(ulong, ulong, Optional<string\>\)

Edits a message

```csharp
public Task<DiscordMessage> EditMessageAsync(ulong channel_id, ulong message_id, Optional<string> content)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`content` [Optional](DSharpPlus.Entities.Optional\-1.md)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

New message content

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_DiscordRestClient_EditMessageAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_Optional_DSharpPlus_Entities_DiscordEmbed__"></a>EditMessageAsync\(ulong, ulong, Optional<DiscordEmbed\>\)

Edits a message

```csharp
public Task<DiscordMessage> EditMessageAsync(ulong channel_id, ulong message_id, Optional<DiscordEmbed> embed)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`embed` [Optional](DSharpPlus.Entities.Optional\-1.md)<[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)\>

New message embed

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_DiscordRestClient_EditMessageAsync_System_UInt64_System_UInt64_DSharpPlus_Entities_DiscordMessageBuilder_System_Boolean_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditMessageAsync\(ulong, ulong, DiscordMessageBuilder, bool, IEnumerable<DiscordAttachment\>\)

Edits a message

```csharp
public Task<DiscordMessage> EditMessageAsync(ulong channel_id, ulong message_id, DiscordMessageBuilder builder, bool suppressEmbeds = false, IEnumerable<DiscordAttachment> attachments = null)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`message\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Message ID

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The builder of the message to edit.

`suppressEmbeds` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether to suppress embeds on the message.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

