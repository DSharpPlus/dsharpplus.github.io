# Class InteractionContext

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents a context for an interaction.

```csharp
public sealed class InteractionContext : BaseContext
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[BaseContext](DSharpPlus.SlashCommands.BaseContext.md) ← 
[InteractionContext](DSharpPlus.SlashCommands.InteractionContext.md)

###### Inherited Members

[BaseContext.Interaction](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Interaction), 
[BaseContext.Client](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Client), 
[BaseContext.Guild](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Guild), 
[BaseContext.Channel](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Channel), 
[BaseContext.User](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_User), 
[BaseContext.Member](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Member), 
[BaseContext.SlashCommandsExtension](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_SlashCommandsExtension), 
[BaseContext.Token](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Token), 
[BaseContext.InteractionId](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_InteractionId), 
[BaseContext.CommandName](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_CommandName), 
[BaseContext.QualifiedName](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_QualifiedName), 
[BaseContext.Type](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Type), 
[BaseContext.Services](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_Services), 
[BaseContext.CreateResponseAsync\(InteractionResponseType, DiscordInteractionResponseBuilder\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_CreateResponseAsync\_DSharpPlus\_InteractionResponseType\_DSharpPlus\_Entities\_DiscordInteractionResponseBuilder\_), 
[BaseContext.CreateResponseAsync\(DiscordInteractionResponseBuilder\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_CreateResponseAsync\_DSharpPlus\_Entities\_DiscordInteractionResponseBuilder\_), 
[BaseContext.CreateResponseAsync\(string, DiscordEmbed, bool\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_CreateResponseAsync\_System\_String\_DSharpPlus\_Entities\_DiscordEmbed\_System\_Boolean\_), 
[BaseContext.CreateResponseAsync\(string, bool\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_CreateResponseAsync\_System\_String\_System\_Boolean\_), 
[BaseContext.CreateResponseAsync\(DiscordEmbed, bool\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_CreateResponseAsync\_DSharpPlus\_Entities\_DiscordEmbed\_System\_Boolean\_), 
[BaseContext.DeferAsync\(bool\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_DeferAsync\_System\_Boolean\_), 
[BaseContext.EditResponseAsync\(DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_EditResponseAsync\_DSharpPlus\_Entities\_DiscordWebhookBuilder\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordAttachment\_\_), 
[BaseContext.DeleteResponseAsync\(\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_DeleteResponseAsync), 
[BaseContext.FollowUpAsync\(DiscordFollowupMessageBuilder\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_FollowUpAsync\_DSharpPlus\_Entities\_DiscordFollowupMessageBuilder\_), 
[BaseContext.EditFollowupAsync\(ulong, DiscordWebhookBuilder, IEnumerable<DiscordAttachment\>\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_EditFollowupAsync\_System\_UInt64\_DSharpPlus\_Entities\_DiscordWebhookBuilder\_System\_Collections\_Generic\_IEnumerable\_DSharpPlus\_Entities\_DiscordAttachment\_\_), 
[BaseContext.DeleteFollowupAsync\(ulong\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_DeleteFollowupAsync\_System\_UInt64\_), 
[BaseContext.GetOriginalResponseAsync\(\)](DSharpPlus.SlashCommands.BaseContext.md\#DSharpPlus\_SlashCommands\_BaseContext\_GetOriginalResponseAsync)

## Properties

### <a id="DSharpPlus_SlashCommands_InteractionContext_ResolvedChannelMentions"></a>ResolvedChannelMentions

Gets the channels mentioned in the command parameters.

```csharp
public IReadOnlyList<DiscordChannel> ResolvedChannelMentions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)\>

### <a id="DSharpPlus_SlashCommands_InteractionContext_ResolvedRoleMentions"></a>ResolvedRoleMentions

Gets the roles mentioned in the command parameters.

```csharp
public IReadOnlyList<DiscordRole> ResolvedRoleMentions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordRole](DSharpPlus.Entities.DiscordRole.md)\>

### <a id="DSharpPlus_SlashCommands_InteractionContext_ResolvedUserMentions"></a>ResolvedUserMentions

Gets the users mentioned in the command parameters.

```csharp
public IReadOnlyList<DiscordUser> ResolvedUserMentions { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordUser](DSharpPlus.Entities.DiscordUser.md)\>

