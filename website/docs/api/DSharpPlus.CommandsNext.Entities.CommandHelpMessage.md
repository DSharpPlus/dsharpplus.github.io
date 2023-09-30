# Struct CommandHelpMessage

Namespace: [DSharpPlus.CommandsNext.Entities](DSharpPlus.CommandsNext.Entities.md)  
Assembly: DSharpPlus.CommandsNext.dll

Represents a formatted help message.

```csharp
public struct CommandHelpMessage
```

## Constructors

### <a id="DSharpPlus_CommandsNext_Entities_CommandHelpMessage__ctor_System_String_DSharpPlus_Entities_DiscordEmbed_"></a>CommandHelpMessage\(string?, DiscordEmbed?\)

Creates a new instance of a help message.

```csharp
public CommandHelpMessage(string? content = null, DiscordEmbed? embed = null)
```

#### Parameters

`content` [string](https://learn.microsoft.com/dotnet/api/system.string)?

Contents of the message.

`embed` [DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)?

Embed to attach to the message.

## Properties

### <a id="DSharpPlus_CommandsNext_Entities_CommandHelpMessage_Content"></a>Content

Gets the contents of the help message.

```csharp
public readonly string? Content { get; }
```

#### Property Value

[string](https://learn.microsoft.com/dotnet/api/system.string)?

### <a id="DSharpPlus_CommandsNext_Entities_CommandHelpMessage_Embed"></a>Embed

Gets the embed attached to the help message.

```csharp
public readonly DiscordEmbed? Embed { get; }
```

#### Property Value

[DiscordEmbed](DSharpPlus.Entities.DiscordEmbed.md)?

