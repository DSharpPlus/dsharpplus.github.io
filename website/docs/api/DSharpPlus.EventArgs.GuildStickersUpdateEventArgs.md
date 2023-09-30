# Class GuildStickersUpdateEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents event args for the <xref href="DSharpPlus.DiscordClient.GuildStickersUpdated" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildStickersUpdateEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildStickersUpdateEventArgs](DSharpPlus.EventArgs.GuildStickersUpdateEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildStickersUpdateEventArgs_Guild"></a>Guild

Gets the guild in which the update occurred.

```csharp
public DiscordGuild Guild { get; }
```

#### Property Value

[DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)

### <a id="DSharpPlus_EventArgs_GuildStickersUpdateEventArgs_StickersAfter"></a>StickersAfter

Gets the list of stickers after the change.

```csharp
public IReadOnlyDictionary<ulong, DiscordMessageSticker> StickersAfter { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

### <a id="DSharpPlus_EventArgs_GuildStickersUpdateEventArgs_StickersBefore"></a>StickersBefore

Gets the list of stickers before the change.

```csharp
public IReadOnlyDictionary<ulong, DiscordMessageSticker> StickersBefore { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordMessageSticker](DSharpPlus.Entities.DiscordMessageSticker.md)\>

