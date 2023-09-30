# Class MessageReactionsClearEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.MessageReactionsCleared" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class MessageReactionsClearEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[MessageReactionsClearEventArgs](DSharpPlus.EventArgs.MessageReactionsClearEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_MessageReactionsClearEventArgs_Channel"></a>Channel

Gets the channel to which this message belongs.

```csharp
public DiscordChannel Channel { get; }
```

#### Property Value

[DiscordChannel](DSharpPlus.Entities.DiscordChannel.md)

#### Remarks

This will be <code>null</code> for an uncached channel, which will usually happen for when this event triggers on
DM channels in which no prior messages were received or sent.

### <a id="DSharpPlus_EventArgs_MessageReactionsClearEventArgs_Guild"></a>Guild

Gets the guild in which the reactions were cleared.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_MessageReactionsClearEventArgs_Message"></a>Message

Gets the message for which the update occurred.

```csharp
public DiscordMessage Message { get; }
```

#### Property Value

[DiscordMessage](DSharpPlus.Entities.DiscordMessage.md)

