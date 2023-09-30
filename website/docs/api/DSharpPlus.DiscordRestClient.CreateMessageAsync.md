# Method CreateMessageAsync

Namespace: [DSharpPlus](DSharpPlus.md)  
Assembly: DSharpPlus.Rest.dll

## <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_System_String_"></a>CreateMessageAsync\(ulong, string\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, string content)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message (text) content

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_DSharpPlus_Entities_DiscordEmbed_"></a>CreateMessageAsync\(ulong, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, DiscordEmbed embed)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>CreateMessageAsync\(ulong, string, DiscordEmbed\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, string content, DiscordEmbed embed)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message (text) content

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_DSharpPlus_Entities_DiscordMessageBuilder_"></a>CreateMessageAsync\(ulong, DiscordMessageBuilder\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, DiscordMessageBuilder builder)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The Discord Message builder.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_DiscordRestClient_CreateMessageAsync_System_UInt64_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>CreateMessageAsync\(ulong, Action<DiscordMessageBuilder\>\)

Sends a message

```csharp
public Task<DiscordMessage> CreateMessageAsync(ulong channel_id, Action<DiscordMessageBuilder> action)
```

### Parameters

`channel\_id` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

Channel ID

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The Discord Message builder.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

