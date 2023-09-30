# Class GuildDownloadCompletedEventArgs

Namespace: [DSharpPlus.EventArgs](DSharpPlus.EventArgs.md)  
Assembly: DSharpPlus.dll

Represents arguments for <xref href="DSharpPlus.DiscordClient.GuildDownloadCompleted" data-throw-if-not-resolved="false"></xref> event.

```csharp
public class GuildDownloadCompletedEventArgs : DiscordEventArgs
```

###### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[EventArgs](https://learn.microsoft.com/dotnet/api/system.eventargs) ← 
[AsyncEventArgs](DSharpPlus.AsyncEvents.AsyncEventArgs.md) ← 
[DiscordEventArgs](DSharpPlus.EventArgs.DiscordEventArgs.md) ← 
[GuildDownloadCompletedEventArgs](DSharpPlus.EventArgs.GuildDownloadCompletedEventArgs.md)

###### Inherited Members

[AsyncEventArgs.Handled](DSharpPlus.AsyncEvents.AsyncEventArgs.md\#DSharpPlus\_AsyncEvents\_AsyncEventArgs\_Handled)

## Properties

### <a id="DSharpPlus_EventArgs_GuildDownloadCompletedEventArgs_Guilds"></a>Guilds

Gets the dictionary of guilds that just finished downloading.

```csharp
public IReadOnlyDictionary<ulong, DiscordGuild> Guilds { get; }
```

#### Property Value

[IReadOnlyDictionary](https://learn.microsoft.com/dotnet/api/system.collections.generic.ireadonlydictionary\-2)<[ulong](https://learn.microsoft.com/dotnet/api/system.uint64), [DiscordGuild](DSharpPlus.Entities.DiscordGuild.md)\>

