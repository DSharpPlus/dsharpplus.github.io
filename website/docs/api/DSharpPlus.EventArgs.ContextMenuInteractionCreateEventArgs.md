# Class ContextMenuInteractionCreateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

```csharp
public sealed class ContextMenuInteractionCreateEventArgs : InteractionCreateEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[InteractionCreateEventArgs](DSharpPlus.EventArgs.InteractionCreateEventArgs.md) ← 
[ContextMenuInteractionCreateEventArgs](DSharpPlus.EventArgs.ContextMenuInteractionCreateEventArgs.md)

###### Inherited Members

[InteractionCreateEventArgs.Interaction](DSharpPlus.EventArgs.InteractionCreateEventArgs.md\#DSharpPlus\_EventArgs\_InteractionCreateEventArgs\_Interaction), 
[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_ContextMenuInteractionCreateEventArgs_TargetMessage"></a>TargetMessage

The message this interaction targets, if applicable.

```csharp
public DiscordMessage TargetMessage { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

### <a id="DSharpPlus_EventArgs_ContextMenuInteractionCreateEventArgs_TargetUser"></a>TargetUser

The user this interaction targets, if applicable.

```csharp
public DiscordUser TargetUser { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

### <a id="DSharpPlus_EventArgs_ContextMenuInteractionCreateEventArgs_Type"></a>Type

The type of context menu that was used. This is never <xref href="DSharpPlus.ApplicationCommandType.SlashCommand" data-throw-if-not-resolved="false"></xref>.

```csharp
public ApplicationCommandType Type { get; }
```

#### Property Value

[ApplicationCommandType](DSharpPlus.ApplicationCommandType.md)

### <a id="DSharpPlus_EventArgs_ContextMenuInteractionCreateEventArgs_User"></a>User

The user that invoked this interaction. Can be casted to a member if this was on a guild.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

