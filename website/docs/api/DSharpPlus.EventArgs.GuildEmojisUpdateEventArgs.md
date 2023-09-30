# Class GuildEmojisUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildEmojisUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildEmojisUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildEmojisUpdateEventArgs](DSharpPlus.EventArgs.GuildEmojisUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildEmojisUpdateEventArgs_EmojisAfter"></a>EmojisAfter

Gets the list of emojis after the change.

```csharp
public IReadOnlyDictionary<ulong, DiscordEmoji> EmojisAfter { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

### <a id="DSharpPlus_EventArgs_GuildEmojisUpdateEventArgs_EmojisBefore"></a>EmojisBefore

Gets the list of emojis before the change.

```csharp
public IReadOnlyDictionary<ulong, DiscordEmoji> EmojisBefore { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordEmoji](DSharpPlus.Entities.DiscordEmoji.md)\>

### <a id="DSharpPlus_EventArgs_GuildEmojisUpdateEventArgs_Guild"></a>Guild

Gets the guild in which the update occurred.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

