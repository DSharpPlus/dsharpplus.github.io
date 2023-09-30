# Class MessageReactionAddEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.MessageReactionAdded" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class MessageReactionAddEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[MessageReactionAddEventArgs](DSharpPlus.EventArgs.MessageReactionAddEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_MessageReactionAddEventArgs_Channel"></a>Channel

Gets the channel to which this message belongs.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

#### Remarks

This will be <code>null</code> for an uncached channel, which will usually happen for when this event triggers on
DM channels in which no prior messages were received or sent.

### <a id="DSharpPlus_EventArgs_MessageReactionAddEventArgs_Emoji"></a>Emoji

Gets the emoji used for this reaction.

```csharp
public DiscordEmoji Emoji { get; }
```

#### Property Value

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

### <a id="DSharpPlus_EventArgs_MessageReactionAddEventArgs_Guild"></a>Guild

Gets the guild in which the reaction was added.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_MessageReactionAddEventArgs_Message"></a>Message

Gets the message for which the update occurred.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

### <a id="DSharpPlus_EventArgs_MessageReactionAddEventArgs_User"></a>User

Gets the user who created the reaction.
<p>This can be cast to a <xref href="DSharpPlus.Entities.DiscordMember" data-throw-if-not-resolved="false"></xref> if the reaction was in a guild.</p>

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

