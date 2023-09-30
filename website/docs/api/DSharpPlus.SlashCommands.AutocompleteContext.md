# Class AutocompleteContext

Namespace: [DSharpPlus.SlashCommands](DSharpPlus.SlashCommands.md)  
Assembly: DSharpPlus.SlashCommands.dll

Represents a context for an autocomplete interaction.

```csharp
public class AutocompleteContext
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[AutocompleteContext](DSharpPlus.SlashCommands.AutocompleteContext.md)

## Properties

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_Channel"></a>Channel

Gets the channel this interaction was executed in.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_Client"></a>Client

Gets the client for this interaction.

```csharp
public DiscordClient Client { get; }
```

#### Property Value

[DiscordClient](DSharpPlus.DiscordClient.md)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_FocusedOption"></a>FocusedOption

The option to auto-fill for.

```csharp
public DiscordInteractionDataOption FocusedOption { get; }
```

#### Property Value

[DiscordInteractionDataOption](DSharpPlus.Entities.DiscordInteractionDataOption.md)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_Guild"></a>Guild

Gets the guild this interaction was executed in.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_Interaction"></a>Interaction

The interaction created.

```csharp
public DiscordInteraction Interaction { get; }
```

#### Property Value

[DiscordInteraction](DSharpPlus.Entities.DiscordInteraction.md)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_Member"></a>Member

Gets the member which executed this interaction, or null if the command is in a DM.

```csharp
public DiscordMember Member { get; }
```

#### Property Value

[DiscordMember](DSharpPlus.Entities.DiscordMember.md)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_OptionValue"></a>OptionValue

The given value of the focused option.

```csharp
public object OptionValue { get; }
```

#### Property Value

[object](https://learn.microsoft.com/dotnet/api/system.object)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_Options"></a>Options

The options already provided.

```csharp
public IReadOnlyList<DiscordInteractionDataOption> Options { get; }
```

#### Property Value

[IReadOnlyList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlylist\-1)<[DiscordInteractionDataOption](DSharpPlus.Entities.DiscordInteractionDataOption.md)\>

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_Services"></a>Services

<p>Gets the service provider.</p>
<p>This allows passing data around without resorting to static members.</p>
<p>Defaults to null.</p>

```csharp
public IServiceProvider Services { get; }
```

#### Property Value

[IServiceProvider](https://learn.microsoft.com/dotnet/api/system.iserviceprovider)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_SlashCommandsExtension"></a>SlashCommandsExtension

Gets the slash command module this interaction was created in.

```csharp
public SlashCommandsExtension SlashCommandsExtension { get; }
```

#### Property Value

[SlashCommandsExtension](DSharpPlus.SlashCommands.SlashCommandsExtension.md)

### <a id="DSharpPlus_SlashCommands_AutocompleteContext_User"></a>User

Gets the user which executed this interaction.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

