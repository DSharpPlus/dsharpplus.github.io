# Class BaseContext

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents a base context for application command contexts.

```csharp
public class BaseContext
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseContext](DSharpPlus.SlashCommands.BaseContext.md)

###### Derived

[ContextMenuContext](DSharpPlus.SlashCommands.ContextMenuContext.md), 
[InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

## Properties

### <a id="DSharpPlus_SlashCommands_BaseContext_Channel"></a>Channel

Gets the channel this interaction was executed in.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_SlashCommands_BaseContext_Client"></a>Client

Gets the client for this interaction.

```csharp
public DiscordClient Client { get; }
```

#### Property Value

[DiscordClient](DSharpPlus.DiscordClient.md)

### <a id="DSharpPlus_SlashCommands_BaseContext_CommandName"></a>CommandName

Gets the name of the command.

```csharp
public string CommandName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_BaseContext_Guild"></a>Guild

Gets the guild this interaction was executed in.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_SlashCommands_BaseContext_Interaction"></a>Interaction

Gets the interaction that was created.

```csharp
public DiscordInteraction Interaction { get; }
```

#### Property Value

[DiscordInteraction](DSharpPlus.Entities.DiscordInteraction.md)

### <a id="DSharpPlus_SlashCommands_BaseContext_InteractionId"></a>InteractionId

Gets the id for this interaction.

```csharp
public ulong InteractionId { get; }
```

#### Property Value

[ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

### <a id="DSharpPlus_SlashCommands_BaseContext_Member"></a>Member

Gets the member which executed this interaction, or null if the command is in a DM.

```csharp
public DiscordMember Member { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_SlashCommands_BaseContext_QualifiedName"></a>QualifiedName

Gets the qualified name of the command.

```csharp
public string QualifiedName { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_BaseContext_Services"></a>Services

<p>Gets the service provider.</p>
<p>This allows passing data around without resorting to static members.</p>
<p>Defaults to null.</p>

```csharp
public IServiceProvider Services { get; }
```

#### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

### <a id="DSharpPlus_SlashCommands_BaseContext_SlashCommandsExtension"></a>SlashCommandsExtension

Gets the slash command module this interaction was created in.

```csharp
public SlashCommandsExtension SlashCommandsExtension { get; }
```

#### Property Value

[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)

### <a id="DSharpPlus_SlashCommands_BaseContext_Token"></a>Token

Gets the token for this interaction.

```csharp
public string Token { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="DSharpPlus_SlashCommands_BaseContext_Type"></a>Type

Gets the type of this interaction.

```csharp
public ApplicationCommandType Type { get; }
```

#### Property Value

[ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

### <a id="DSharpPlus_SlashCommands_BaseContext_User"></a>User

Gets the user which executed this interaction.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

## Methods

### <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_DSharpPlus_InteractionResponseType_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateResponseAsync\(InteractionResponseType, DiscordInteractionResponseBuilder\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(InteractionResponseType type, DiscordInteractionResponseBuilder builder = null)
```

#### Parameters

`type` [InteractionResponseType](DSharpPlus.InteractionResponseType.md)

The type of the response.

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data to be sent, if any.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_DSharpPlus_Entities_DiscordInteractionResponseBuilder_"></a>CreateResponseAsync\(DiscordInteractionResponseBuilder\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(DiscordInteractionResponseBuilder builder)
```

#### Parameters

`builder` [DiscordInteractionResponseBuilder](DSharpPlus.Entities.DiscordInteractionResponseBuilder.md)

The data to be sent, if any.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_System_String_DSharpPlus_Entities_DiscordEmbed_System_Boolean_"></a>CreateResponseAsync\(string, DiscordEmbed, bool\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(string content, DiscordEmbed embed, bool ephemeral = false)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content to send in the response.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to send in the response.

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_System_String_System_Boolean_"></a>CreateResponseAsync\(string, bool\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(string content, bool ephemeral = false)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)

Content to send in the response.

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_CreateResponseAsync_DSharpPlus_Entities_DiscordEmbed_System_Boolean_"></a>CreateResponseAsync\(DiscordEmbed, bool\)

Creates a response to this interaction.
<p>You must create a response within 3 seconds of this interaction being executed; if the command has the potential to take more than 3 seconds, use <xref href="DSharpPlus.SlashCommands.BaseContext.DeferAsync(System.Boolean)" data-throw-if-not-resolved="false"></xref> at the start, and edit the response later.</p>

```csharp
public Task CreateResponseAsync(DiscordEmbed embed, bool ephemeral = false)
```

#### Parameters

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)

Embed to send in the response.

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_DeferAsync_System_Boolean_"></a>DeferAsync\(bool\)

Creates a deferred response to this interaction.

```csharp
public Task DeferAsync(bool ephemeral = false)
```

#### Parameters

`ephemeral` [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

Whether the response should be ephemeral.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_DeleteFollowupAsync_System_UInt64_"></a>DeleteFollowupAsync\(ulong\)

Deletes a followup message.

```csharp
public Task DeleteFollowupAsync(ulong followupMessageId)
```

#### Parameters

`followupMessageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the followup message to delete.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_DeleteResponseAsync"></a>DeleteResponseAsync\(\)

Deletes the interaction response.

```csharp
public Task DeleteResponseAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

### <a id="DSharpPlus_SlashCommands_BaseContext_EditFollowupAsync_System_UInt64_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditFollowupAsync\(ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits a followup message.

```csharp
public Task<DiscordMessage> EditFollowupAsync(ulong followupMessageId, DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`followupMessageId` [ulong](https://learn.microsoft.com/dotnet/api/system.uint64)

The id of the followup message to edit.

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The webhook builder.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_SlashCommands_BaseContext_EditResponseAsync_DSharpPlus_Entities_DiscordWebhookBuilder_System_Collections_Generic_IEnumerable_DSharpPlus_Entities_DiscordAttachment__"></a>EditResponseAsync\(DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)

Edits the interaction response.

```csharp
public Task<DiscordMessage> EditResponseAsync(DiscordWebhookBuilder builder, IEnumerable<DiscordAttachment> attachments = null)
```

#### Parameters

`builder` [DiscordWebhookBuilder](DSharpPlus.Entities.DiscordWebhookBuilder.md)

The data to edit the response with.

`attachments` [IEnumerable](https://learn.microsoft.com/dotnet/api/system.collections.generic.ienumerable\-1)<[DiscordAttachment](DSharpPlus.Entities.DiscordAttachment.md)\>

Attached files to keep.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

### <a id="DSharpPlus_SlashCommands_BaseContext_FollowUpAsync_DSharpPlus_Entities_DiscordFollowupMessageBuilder_"></a>FollowUpAsync\(DiscordFollowupMessageBuilder\)

Creates a follow up message to the interaction.

```csharp
public Task<DiscordMessage> FollowUpAsync(DiscordFollowupMessageBuilder builder)
```

#### Parameters

`builder` [DiscordFollowupMessageBuilder](DSharpPlus.Entities.DiscordFollowupMessageBuilder.md)

The message to be sent, in the form of a webhook.

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The created message.

### <a id="DSharpPlus_SlashCommands_BaseContext_GetOriginalResponseAsync"></a>GetOriginalResponseAsync\(\)

Gets the original interaction response.

```csharp
public Task<DiscordMessage> GetOriginalResponseAsync()
```

#### Returns

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)\>

The original interaction response.

