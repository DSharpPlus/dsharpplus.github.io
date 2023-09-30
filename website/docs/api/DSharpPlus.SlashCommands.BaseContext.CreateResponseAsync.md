# Method CreateResponseAsync

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

## <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_DSharpPlus_InteractionResponseType_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateResponseAsync\(InteractionResponseType, DiscordInteractionResponseBuilder\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(InteractionResponseType type, DiscordInteractionResponseBuilder builder = null)
```

### Parameters

`type` [InteractionResponseType](DSharpPlus.InteractionResponseType.md)

The type of the response.

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data to be sent, if any.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateResponseAsync\(DiscordInteractionResponseBuilder\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(DiscordInteractionResponseBuilder builder)
```

### Parameters

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data to be sent, if any.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_System_String_DSharpPlus_Entities_DiscordEmbed_System_Boolean_"></a>CreateResponseAsync\(string, DiscordEmbed, bool\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(string content, DiscordEmbed embed, bool ephemeral = false)
```

### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content to send in the response.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to send in the response.

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_System_String_System_Boolean_"></a>CreateResponseAsync\(string, bool\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(string content, bool ephemeral = false)
```

### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content to send in the response.

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

## <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_DSharpPlus_Entities_DiscordEmbed_System_Boolean_"></a>CreateResponseAsync\(DiscordEmbed, bool\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(DiscordEmbed embed, bool ephemeral = false)
```

### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to send in the response.

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

