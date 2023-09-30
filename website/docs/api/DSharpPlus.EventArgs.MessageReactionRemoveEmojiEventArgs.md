# Class MessageReactionRemoveEmojiEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.MessageReactionRemovedEmoji" data-throw-if-not-resolved="false"></xref>

```csharp
public sealed class MessageReactionRemoveEmojiEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[MessageReactionRemoveEmojiEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEmojiEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEmojiEventArgs_Channel"></a>Channel

Gets the channel the removed reactions were in.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEmojiEventArgs_Emoji"></a>Emoji

Gets the emoji of the reaction that was removed.

```csharp
public DiscordEmoji Emoji { get; }
```

#### Property Value

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEmojiEventArgs_Guild"></a>Guild

Gets the guild the removed reactions were in.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEmojiEventArgs_Message"></a>Message

Gets the message that had the removed reactions.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

