# Class MessageReactionRemoveEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.MessageReactionRemoved" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class MessageReactionRemoveEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[MessageReactionRemoveEventArgs](DSharpPlus.EventArgs.MessageReactionRemoveEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEventArgs_Channel"></a>Channel

Gets the channel to which this message belongs.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

#### Remarks

This will be <code>null</code> for an uncached channel, which will usually happen for when this event triggers on
DM channels in which no prior messages were received or sent.

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEventArgs_Emoji"></a>Emoji

Gets the emoji used for this reaction.

```csharp
public DiscordEmoji Emoji { get; }
```

#### Property Value

[DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEventArgs_Guild"></a>Guild

Gets the guild in which the reaction was deleted.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEventArgs_Message"></a>Message

Gets the message for which the update occurred.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

### <a id="DSharpPlus_EventArgs_MessageReactionRemoveEventArgs_User"></a>User

Gets the users whose reaction was removed.

```csharp
public DiscordUser User { get; }
```

#### Property Value

[DiscordUser](DSharpPlus.Entities.DiscordUser.md)

