# Method RespondAsync

Namespace: [DSharpPlus.CommandsNext](DSharpPlus.CommandsNext.md)  
Assembly: DSharpPlus.CommandsNext.dll

## <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_System_String_"></a>RespondAsync\(string\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(string content)
```

### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message to respond with.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_DSharpPlus_Entities_DiscordEmbed_"></a>RespondAsync\(DiscordEmbed\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(DiscordEmbed embed)
```

### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>RespondAsync\(string, DiscordEmbed\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(string content, DiscordEmbed embed)
```

### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Message to respond with.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to attach.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_DSharpPlus_Entities_DiscordMessageBuilder_"></a>RespondAsync\(DiscordMessageBuilder\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(DiscordMessageBuilder builder)
```

### Parameters

`builder` [DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)

The Discord Message builder.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

## <a id="DSharpPlus_CommandsNext_CommandContext_RespondAsync_System_Action_DSharpPlus_Entities_DiscordMessageBuilder__"></a>RespondAsync\(Action<DiscordMessageBuilder\>\)

Quickly respond to the message that triggered the command.

```csharp
public Task<DiscordMessage> RespondAsync(Action<DiscordMessageBuilder> action)
```

### Parameters

`action` [Action](https://learn.microsoft.com/dotnet/api/system.action\-1)<[DiscordMessageBuilder](DSharpPlus.Entities.DiscordMessageBuilder.md)\>

The Discord Message builder.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

