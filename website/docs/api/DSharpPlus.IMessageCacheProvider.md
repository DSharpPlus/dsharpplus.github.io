# Interface IMessageCacheProvider

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.dll

```csharp
public interface IMessageCacheProvider
```

## Methods

### <a id="DSharpPlus_IMessageCacheProvider_Add_DSharpPlus_Entities_DiscordMessage_"></a>Add\(DiscordMessage\)

Add a <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> object to the cache.

```csharp
void Add(DiscordMessage message)
```

#### Parameters

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> object to add to the cache.

### <a id="DSharpPlus_IMessageCacheProvider_Remove_System_UInt64_"></a>Remove\(ulong\)

Remove the <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> object associated with the message ID from the cache.

```csharp
void Remove(ulong messageId)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message to remove from the cache.

### <a id="DSharpPlus_IMessageCacheProvider_TryGet_System_UInt64_DSharpPlus_Entities_DiscordMessage__"></a>TryGet\(ulong, out DiscordMessage?\)

Try to get a <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> object associated with the message ID from the cache.

```csharp
bool TryGet(ulong messageId, out DiscordMessage? message)
```

#### Parameters

`messageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The ID of the message to retrieve from the cache.

`message` [DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)?

The <xref href="DSharpPlus.Entities.DiscordMessage" data-throw-if-not-resolved="false"></xref> object retrieved from the cache, if it exists; null otherwise.

#### Returns

[bool](https://learn.microsoft.com/dotnet/api/system.boolean)

<a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">true</a> if the message can be retrieved from the cache, <a href="https://learn.microsoft.com/dotnet/csharp/language-reference/builtin-types/bool">false</a> otherwise.

